# LDIF Training Instructions

### Train with this
```
python train.py --dataset_directory training_data/ --experiment_name test --model_type ldif
```

### Eval with this
```
python eval.py --dataset_directory training_data/ --experiment_name bike --split train --save_results --save_meshes --save_ldifs --result_directory ring_results
```