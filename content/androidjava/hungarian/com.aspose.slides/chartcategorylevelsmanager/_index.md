---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides for Android Java API referenciája
description: A diagramkategória szintek értékeinek kezelett tárolója.
type: docs
url: /hu/com.aspose.slides/chartcategorylevelsmanager/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

A diagramkategória szintek értékeinek kezelt tárolója.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

Visszaadja a meghatározott szinthez tartozó IChartDataCell objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

Beállítja a csoportosítási elemet a meghatározott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

Törli a csoportosítási elemet a meghatározott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |