---
title: set_external_workbook method
second_title: Aspose.Slides pro Python přes .NET - reference API
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Nastaví externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| workbook_path | **str** | Cesta k cílovému sešitu |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externí sešit není k dispozici nebo nelze načíst. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Nastaví externí sešit jako zdroj dat pro graf.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| workbook_path | **str** | Cesta k cílovému sešitu |
| update_chart_data | **bool** | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu. <br/><br/>             Data grafu nebudou načtena a aktualizována z cílového sešitu. Lze použít, když cílový sešit neexistuje nebo není k dispozici.<br/><br/>             Pokud je hodnota true, data grafu budou aktualizována z cílového sešitu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externí sešit není k dispozici nebo nelze načíst. |



### Viz také
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)