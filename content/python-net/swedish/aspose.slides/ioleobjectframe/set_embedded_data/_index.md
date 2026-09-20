---
title: set_embedded_data method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Ställer in information om OLE-inbäddad data.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo) | Inbäddad data [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo) |

### Anmärkningar

Den här metoden ändrar objektets egenskaper för att återspegla den nya datan och 
            sätter IsObjectLink flaggan till false, vilket indikerar att OLE-objektet är inbäddat.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När embeddedData-parameter är None. |



### Se också
* klass [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)
* klass [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)