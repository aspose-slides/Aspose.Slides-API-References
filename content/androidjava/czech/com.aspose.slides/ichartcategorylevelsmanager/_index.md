---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
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
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Nastavuje položku seskupení pro definovanou úroveň. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Odstraní položku seskupení pro definovanou úroveň. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Vrací objekt IChartDataCell pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int |  |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Nastavuje položku seskupení pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int | int úroveň kategorie |
| value | java.lang.Object | Objekt položky seskupení |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Odstraní položku seskupení pro definovanou úroveň.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| level | int | int úroveň kategorie |