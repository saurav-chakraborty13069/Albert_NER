# BERTNER
Pytorch Bertner


python run_albert_ner.py --data_dir=data/usa/ --bert_model=albert-base-v1 --task_name=ner --output_dir=out --max_seq_length=128 --do_train --num_train_epochs 5 --do_eval --warmup_proportion=0.4
