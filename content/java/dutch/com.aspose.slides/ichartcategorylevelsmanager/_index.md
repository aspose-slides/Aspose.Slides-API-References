---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /nl/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Beheerde container van de waarden van de categoriëniveaus van het diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retourneert IChartDataCell object voor gedefinieerd niveau. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Stelt groeperingsitem in voor gedefinieerd niveau. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Verwijdert groeperingsitem voor gedefinieerd niveau. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Retourneert IChartDataCell object voor gedefinieerd niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int |  |

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Stelt groeperingsitem in voor gedefinieerd niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int | Categorie niveau int |
| value | java.lang.Object | Groeperingsitem Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Verwijdert groeperingsitem voor gedefinieerd niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int | Categorie niveau int |