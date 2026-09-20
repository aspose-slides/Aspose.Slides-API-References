---
title: insert_ole_object_frame method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

### Vrací

Nově vytvořený [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulovým indexem, na který se vloží rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo) | Informace o vložených datech OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Vytvoří nový rámec OLE objektu a vloží jej do kolekce tvarů na určeném indexu.

### Vrací

Nově vytvořený [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulovým indexem, na který se vloží rámec OLE objektu. |
| x | **float** | Souřadnice x nového rámce OLE, v bodech. |
| y | **float** | Souřadnice y nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| class_name | **str** | Název třídy OLE objektu. |
| path | **str** | Cesta k propojenému souboru. <br/><br/>Tato cesta je v prezentaci uložena přesně tak, jak je.<br/><br/>            Pokud je zadána relativní cesta, soubor nebude přístupný při otevření<br/><br/>            prezentace z jiného adresáře. |



### Viz také
* třída [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)
* třída [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)