

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.model_pruning.apply_mask

``` python
apply_mask(
    x,
    scope=''
)
```



Defined in [`tensorflow/contrib/model_pruning/python/pruning.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.5/tensorflow/contrib/model_pruning/python/pruning.py).

Apply mask to a given weight tensor.

#### Args:

* <b>`x`</b>: Input weight tensor
* <b>`scope`</b>: The current variable scope. Defaults to ""

#### Returns:

Tensor representing masked_weights