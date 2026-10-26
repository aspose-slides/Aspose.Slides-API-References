---
title: insert_ole_object_frame method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

Nově vytvořený [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se vloží rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo) | Informace o vložených datech OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na zadaném indexu.

### Vrací

Nově vytvořený OLE objekt.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se vloží rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| class_name | **str** | Název třídy OLE objektu. |
| path | **str** | Cesta k propojenému souboru. <br/><br/>Tato cesta je v prezentaci uložena doslovně.<br/><br/>            Pokud je zadána relativní cesta, soubor bude nedostupný při otevírání<br/><br/>            prezentace z jiného adresáře. |



### Viz také
* třída [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)
* třída [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)