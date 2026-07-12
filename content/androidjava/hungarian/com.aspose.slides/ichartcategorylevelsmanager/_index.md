---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: A diagram kategória szintjeinek értékeinek kezelett tárolója.
type: docs
url: /hu/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

A diagram kategória szintjeinek értékeinek kezelett tárolója.
## Metódusok

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Visszaadja a meghatározott szint IChartDataCell objektumát. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Beállítja a csoportosítási elemet a meghatározott szinthez. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Törli a csoportosítási elemet a meghatározott szintnél. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Visszaadja a meghatározott szint IChartDataCell objektumát.

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
| level | int | Kategória szint int |
| value | java.lang.Object | Csoportosítási elem Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Törli a csoportosítási elemet a meghatározott szintnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | int | Kategória szint int |