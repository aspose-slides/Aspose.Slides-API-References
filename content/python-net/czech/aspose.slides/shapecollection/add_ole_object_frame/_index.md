---
title: add_ole_object_frame method
second_title: Aspose.Slides pro Python přes .NET – Dokumentace API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového rámce OLE, v bodech. |
| y | **float** | Y-souřadnice nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo) | Informace o vložených OLE datech ([`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Vytvoří nový rámec OLE objektu a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového rámce OLE, v bodech. |
| y | **float** | Y-souřadnice nového rámce OLE, v bodech. |
| width | **float** | Šířka nového rámce OLE, v bodech. |
| height | **float** | Výška nového rámce OLE, v bodech. |
| class_name | **str** | Název třídy OLE objektu. |
| path | **str** | Cesta k propojenému souboru. <br/><br/>Tato cesta je v prezentaci uložena doslova.<br/><br/>            Pokud je zadána relativní cesta, soubor bude při otevření<br/><br/>            prezentace z jiného adresáře nedostupný. |



### Viz také
* třída [`IOleEmbeddedDataInfo`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo)
* třída [`IOleObjectFrame`](/slides/python-net/cs/aspose.slides/ioleobjectframe)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)