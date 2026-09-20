---
title: set_embedded_data method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Mengatur informasi tentang data OLE yang disematkan.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) | Data yang disematkan [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) |

### Remarks
Metode ini mengubah properti objek untuk mencerminkan data baru dan 
            mengatur flag IsObjectLink menjadi false, yang menunjukkan bahwa objek OLE disematkan.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter embeddedData bernilai None. |



### See Also
* class [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)