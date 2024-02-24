## **MCLDA**

![model](D:\PG_WSL\WCL\第二篇\部件\model.jpg)

##### **This is the data and code for our paper: A Meta-Contrastive Learning with Data Augmentation Framework for Zero-Shot Stance Detection**

---

## Package Dependencies:

- cuda >= 11.7
- pytorch == 2.0.0
- python >= 3.9

---

## **Datasets**:

- VAST: contains news comment data from thousands of targets.
- SEM16: comprises Tweet data from six targets.
- WT-WT: a Tweet stance detection dataset focuses on discussions of merger and acquisition (M&A) operations between companies.

---

## Documentation:

```
--src
  --utils
  	|--augment.py
  	|--data_helper.py
  	|--evaluation.py
  	|--model_utils.py
  	|--modeling.py
  	|--preprocessing.py
  |--train_model.py

--data
  │--VAST
  |--SEM16
  |--WT-WT
README.md
```

---

## Train:

python ./src/train_model.py
