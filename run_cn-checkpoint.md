

斗破苍穹 input4
python data/shakespeare_char/prepare_input4.py
python train.py config/train_shakespeare_char.py
python sample.py --out_dir=out-shakespeare-char --start=萧炎大喊一声：“斗气化马！”
python sample.py --out_dir=out-shakespeare-char


斗破苍穹1-500 input1
python data/shakespeare_char/prepare_input1.py
python train.py config/train_shakespeare_char.py
python sample.py --out_dir=out-shakespeare-char --start=萧炎回答说




1
python train.py config/train_doupo_char.py
python sample.py --out_dir=out-doupo-char

wanmei
python data/wanmei_char/prepare.py
python train.py config/train_wanmei_char.py
python sample.py --out_dir=out-wanmei-char

zhetian 
python data/zhetian_char/prepare.py
python train.py config/train_zhetian_char.py
python sample.py --out_dir=out-zhetian-char


python ./generate.py --length=500 --nsamples=4 --prefix=石昊  --fast_pattern --save_samples --save_samples_path=/mnt/xx


git config --global user.email "24212020123@m.fudan.edu.cn"
git config --global user.name "LLLLLA7"
git init
git-lfs install
git-lfs track "*.bin"
git add .
git add .gitattributes
git commit -m "first commit"
git remote add origin git@github.com:LLLLLA7/AI-Design-Mid-term.git
git push -u origin main

git config --global user.email "24212020123@m.fudan.edu.cn"
git config --global user.name "LLLLLA7"
git init
git-lfs install
git-lfs track "*.pt"
git add .
git add .gitattributes
git commit -m "first commit"
git remote add origin git@github.com:LLLLLA7/first-commit-nanogpt.git
git push -u origin main
git push -f origin master