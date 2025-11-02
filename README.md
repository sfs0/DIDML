# 训练和测试

```markdown
# training:
python train_DIDML-SemiCD.py --epoch 100 --batchsize 16 --gpu_id '0' --data_name 'LEVIR' --train_ratio 0.05 --model_name 'DIDML_LEVIR'
python train_DIDML-SemiCD.py --epoch 100 --batchsize 16 --gpu_id '0' --data_name 'WHU' --train_ratio 0.2 --model_name 'DIDML_WHU'
python train_DIDML-SemiCD.py --epoch 100 --batchsize 16 --gpu_id '0' --data_name 'GoogleGZ' --train_ratio 0.2 --model_name 'DIDML_GoogleGZ'

# testing:
python test_DIDML-SemiCD.py --gpu_id '0' --data_name 'LEVIR' --model_name 'DIDML_LEVIR'
python test_DIDML-SemiCD.py --gpu_id '0' --data_name 'WHU' --model_name 'DIDML_WHU'
python test_DIDML-SemiCD.py --gpu_id '0' --data_name 'GoogleGZ' --model_name 'DIDML_GoogleGZ'
```
