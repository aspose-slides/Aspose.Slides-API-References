---
title: set_embedded_data method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Legt Informationen über OLE eingebettete Daten fest.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo) | Eingebettete Daten [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo) |

### Hinweise

This method changes the properties of the object to reflect the new data and 
            sets the IsObjectLink flag to false, indicating that the OLE object is embedded.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter embeddedData None ist. |



### Siehe auch
* Klasse [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo)
* Klasse [`IOleObjectFrame`](/slides/python-net/de/aspose.slides/ioleobjectframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)