# ccfd-seldon-model

Seldon model trained with the Kaggle credit card fraud dataset.

To build the model:

```shell
$ s2i build https://github.com/ruivieira/ccfd-seldon-model.git seldonio/seldon-core-s2i-python3 ruivieira/ccfd-seldon-model
```