---
title: set_metered_key method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/metered/set_metered_key/
weight: 60
---


## set_metered_key {#str-str}
Sets metered public and private key.
            If you purchase metered license, when start application, this API should be called, normally, this is enough. 
            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, 
            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| public_key | **str** | public key |
| private_key | **str** | private key |



### See Also
* class [`Metered`](/slides/python-net/aspose.slides/metered)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

