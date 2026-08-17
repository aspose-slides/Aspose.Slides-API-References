---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Verwalteter Container der Werte der Diagrammkategorienebenen.
type: docs
url: /de/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Verwalteter Container der Werte der Diagrammkategorienebenen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Gibt das IChartDataCell-Objekt für die angegebene Ebene zurück. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Setzt das Gruppierungselement für die angegebene Ebene. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Löscht das Gruppierungselement für die angegebene Ebene. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Gibt das IChartDataCell-Objekt für die angegebene Ebene zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| level | int |  |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Setzt das Gruppierungselement für die angegebene Ebene.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| level | int | Kategorienebene int |
| value | java.lang.Object | Gruppierungselement-Objekt |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Löscht das Gruppierungselement für die angegebene Ebene.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| level | int | Kategorienebene int |