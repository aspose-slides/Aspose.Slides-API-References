---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/ioleobjectframe/set_embedded_data/
weight: 40
---


## set_embedded_data {#IOleEmbeddedDataInfo}
Sets information about OLE embedded data.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| embedded_data | IOleEmbeddedDataInfo | Embedded data [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) |

### Remarks

This method changes the properties of the object to reflect the new data and 
            sets the IsObjectLink flag to false, indicating that the OLE object is embedded.

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | When embeddedData parameter is null. |



