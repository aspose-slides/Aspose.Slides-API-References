---
title: set_external_workbook method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/set_external_workbook/
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
| **RuntimeError(Proxy error(InvalidOperationException))** | Externí sešit není k dispozici nebo jej nelze načíst. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Nastaví externí sešit jako zdroj dat pro graf.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| workbook_path | **str** | Cesta k cílovému sešitu |
| update_chart_data | **bool** | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu.<br/><br/>Data grafu nebudou načtena a aktualizována z cílového sešitu. Lze použít, když cílový sešit neexistuje nebo není k dispozici.<br/><br/>Pokud je hodnota true, data grafu budou aktualizována z cílového sešitu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externí sešit není k dispozici nebo jej nelze načíst. |

### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)