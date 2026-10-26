---
title: to_png method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Převede vstupní prezentaci na sadu obrázků ve formátu PNG.  
            Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", 
            výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Vstupní prezentace. |
| output_file_name | **str** | Jméno výstupního souboru. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Převede vstupní prezentaci na sadu obrázků ve formátu PNG.  
            Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", 
            výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Vstupní prezentace |
| output_file_name | **str** | Jméno výstupního souboru. |
| image_size | [`Size`](/slides/python-net/cs/aspose.slides/size) | Velikost každého vygenerovaného obrázku. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Převede vstupní prezentaci na sadu obrázků ve formátu PNG.  
            Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", 
            výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Vstupní prezentace. |
| output_file_name | **str** | Jméno výstupního souboru. |
| scale | **float** | Měřítko použité na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti renderování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Viz také
* třída [`Convert`](/slides/python-net/cs/aspose.slides.lowcode/convert)
* třída [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions)
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* třída [`Size`](/slides/python-net/cs/aspose.slides/size)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)