---
title: to_tiff method
second_title: Aspose.Slides pro Python prostřednictvím .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF.  
            Pokud je název výstupního souboru zadán jako "myPath/myFilename.tiff", 
            výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Vstupní prezentace. |
| output_file_name | **str** | Název výstupního souboru. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Převádí vstupní prezentaci do formátu TIFF s vlastním nastavením.
            Pokud je název výstupního souboru zadán jako "myPath/myFilename.tiff" a `multipage` je `false`, 
            výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku.
            V opačném případě, pokud je `multipage` `true`, výsledek bude vícestránkový dokument "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Vstupní prezentace. |
| output_file_name | **str** | Název výstupního souboru. |
| options | [`ITiffOptions`](/slides/python-net/cs/aspose.slides.export/itiffoptions) | Možnosti ukládání TIFF. |
| multipage | **bool** | Určuje, zda má být generovaný dokument TIFF vícestránkový. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Viz také
* třída [`Convert`](/slides/python-net/cs/aspose.slides.lowcode/convert)
* třída [`ITiffOptions`](/slides/python-net/cs/aspose.slides.export/itiffoptions)
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)