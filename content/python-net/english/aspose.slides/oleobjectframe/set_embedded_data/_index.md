---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/oleobjectframe/set_embedded_data/
weight: 60
---


## set_embedded_data {#asposeslidesioleembeddeddatainfo}
Sets information about OLE embedded data.

            This method changes the properties of the object to reflect the new data and 
            sets the IsObjectLink flag to false, indicating that the OLE object is embedded.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) | Embedded data [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | When embeddedData parameter is None. |



### See Also
* class [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)
* class [`OleObjectFrame`](/slides/python-net/aspose.slides/oleobjectframe)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

