---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Spravovaný kontejner hodnot úrovní kategorií grafu.
type: docs
url: /cs/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Spravovaný kontejner hodnot úrovní kategorií grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Vrací objekt IChartDataCell pro definovanou úroveň. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Nastavuje seskupovací položku pro definovanou úroveň. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Odstraňuje seskupovací položku pro definovanou úroveň. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Vrací objekt IChartDataCell pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int |  |

**Návratová hodnota:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Nastavuje seskupovací položku pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int | Úroveň kategorie int |
| value | java.lang.Object | Objekt seskupovací položky |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Odstraňuje seskupovací položku pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int | Úroveň kategorie int |