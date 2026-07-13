---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides voor Android via Java API Referentie
description: Beheerde container van de waarden van de chartcategorie-niveaus.
type: docs
url: /nl/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Beheerde container van de waarden van de chartcategorie-niveaus.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Retourneert IChartDataCell object voor het gedefinieerde niveau. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Stelt groeperingsitem in voor het gedefinieerde niveau. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Verwijdert groeperingsitem voor het gedefinieerde niveau. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Retourneert IChartDataCell object voor het gedefinieerde niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int |  |

**Retour:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Stelt groeperingsitem in voor het gedefinieerde niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int | Categorie niveau int |
| value | java.lang.Object | Groeperingsitem Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Verwijdert groeperingsitem voor het gedefinieerde niveau.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | int | Categorie niveau int |