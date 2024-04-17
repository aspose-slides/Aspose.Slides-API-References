---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ioleobjectframe/set_embedded_data/
weight: 60
---


## set_embedded_data {#ioleembeddeddatainfo}
Sets information about OLE embedded data.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) | Embedded data [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) |

### Remarks

This method changes the properties of the object to reflect the new data and 
            sets the IsObjectLink flag to false, indicating that the OLE object is embedded.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | When embeddedData parameter is null. |



### See Also
* class [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/aspose.slides/ioleobjectframe)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

