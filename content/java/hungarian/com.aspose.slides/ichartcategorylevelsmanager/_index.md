---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: A diagram kategória szintjeinek értékeit kezelő tároló.
type: docs
url: /hu/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

A diagram kategória szintjeinek értékeit kezelő tároló.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Visszaad egy IChartDataCell objektumot a megadott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int |  |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Beállítja a csoportosítási elemet a meghatározott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int | Category level int |
| value | java.lang.Object | Csoportosítási elem Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Törli a csoportosítási elemet a megadott szinthez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int | Category level int |