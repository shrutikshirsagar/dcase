WIP
example to run it:
python train.py --batch-size 32 --valid-batch-size 64 --epochs 500 --lr 1.0 --l2 1e-4 --smoothing 0.05 --warmup 4000 --momentum 0.9 --max-gnorm 30 --checkpoint-path /your path --data-path /traindata path/ --valid-data-path /testdatapath --n-workers 8 --model resnet --save-every 20 --eval-every 100 --logdir resnetpath
