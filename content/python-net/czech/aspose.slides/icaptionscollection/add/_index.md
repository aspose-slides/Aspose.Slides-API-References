---
title: add method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Přidá uzavřené titulky WebVTT na konec kolekce.

### Vrací

Přidaná instance [`ICaptions`](/slides/python-net/cs/aspose.slides/icaptions).



```python
def add(self, label, file_path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| label | **str** | Štítek uzavřených titulků. |
| file_path | **str** | Cesta k souboru WebVTT. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvolána, pokud je `file_path` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud je `file_path` prázdná. |


## add(self, label, stream) {#str-iorawiobase}
Přidá uzavřené titulky WebVTT na konec kolekce z proudu.

### Vrací

Přidaná instance [`ICaptions`](/slides/python-net/cs/aspose.slides/icaptions).



```python
def add(self, label, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| label | **str** | Štítek uzavřených titulků. |
| stream | **io.RawIOBase** | Vstupní proud obsahující data ve formátu WebVTT. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvolána, pokud je `stream` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud vstupní data nejsou ve formátu WebVTT. |



### Viz také
* třída [`ICaptions`](/slides/python-net/cs/aspose.slides/icaptions)
* třída [`ICaptionsCollection`](/slides/python-net/cs/aspose.slides/icaptionscollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)