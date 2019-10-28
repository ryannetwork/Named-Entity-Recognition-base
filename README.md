# Named-Entity-Recognition-base
测试命名实体识别 (Named Entity Recognition, NER) 模型及数据。

### GermEval2014

参考 [Transformers Examples](https://huggingface.co/transformers/examples.html#examples) 中的 [`run_ner.py`](https://github.com/huggingface/transformers/blob/master/examples/run_ner.py)。构建相同的训练模型。结果为：

| 项        | 值     |
| --------- | ------ |
| loss      | 0.0958 |
| f1        | 0.8300 |
| precision | 0.8183 |
|           | 0.8440 |

### dh_msra

使用 BERT 训练 [dh_msra](https://github.com/SophonPlus/ChineseNlpCorpus/raw/master/datasets/dh_msra/dh_msra.zip) 数据集。

