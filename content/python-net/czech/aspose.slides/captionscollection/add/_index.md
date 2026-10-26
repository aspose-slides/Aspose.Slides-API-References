---
title: add method
second_title: Aspose.Slides pro Python přes .NET - referenční API
description: 
type: docs
url: /cs/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Přidá uzavřené titulky ve formátu WebVTT na konec kolekce.

### Returns

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
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvoláno, pokud je `file_path` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud je `file_path` prázdný. |


## add(self, label, stream) {#str-iorawiobase}
Přidá uzavřené titulky ve formátu WebVTT na konec kolekce ze streamu.

### Returns

Přidaná instance [`ICaptions`](/slides/python-net/cs/aspose.slides/icaptions).



```python
def add(self, label, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| label | **str** | Štítek uzavřených titulků. |
| stream | **io.RawIOBase** | Vstupní stream obsahující data ve formátu WebVTT. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvoláno, pokud je `stream` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, pokud vstupní data nejsou ve formátu WebVTT. |



### Viz také
* třída [`CaptionsCollection`](/slides/python-net/cs/aspose.slides/captionscollection)
* třída [`ICaptions`](/slides/python-net/cs/aspose.slides/icaptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)