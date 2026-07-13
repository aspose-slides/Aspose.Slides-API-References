---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Zarządzany kontener wartości poziomów kategorii wykresu.
type: docs
url: /pl/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Zarządzany kontener wartości poziomów kategorii wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Zwraca obiekt IChartDataCell dla określonego poziomu. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Ustawia element grupowania dla określonego poziomu. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Usuwa element grupowania dla określonego poziomu. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Zwraca obiekt IChartDataCell dla określonego poziomu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| level | int |  |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Ustawia element grupowania dla określonego poziomu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| level | int | Poziom kategorii int |
| value | java.lang.Object | Obiekt elementu grupowania |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Usuwa element grupowania dla określonego poziomu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| level | int | Poziom kategorii int |