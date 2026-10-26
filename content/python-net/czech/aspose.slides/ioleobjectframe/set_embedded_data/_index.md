---
title: set_embedded_data method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Nastavuje informace o vložených OLE datech.

```python
def set_embedded_data(self, embedded_data):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo) | Vložená data [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo) |

### Poznámky

Tato metoda mění vlastnosti objektu tak, aby odrážely nová data a
            nastavuje příznak IsObjectLink na false, což indikuje, že OLE objekt je vložený.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr embeddedData nastaven na None. |

### Viz také
* třída [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)
* třída [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)