---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Verwalteter Container der Werte der Diagramm-Kategorienstufen.
type: docs
url: /de/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Verwaltercontainer der Werte der Diagramm-Kategorienstufen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Gibt ein IChartDataCell-Objekt für die angegebene Stufe zurück. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Legt das Gruppierungselement für die angegebene Stufe fest. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Entfernt das Gruppierungselement für die angegebene Stufe. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Gibt ein IChartDataCell-Objekt für die angegebene Stufe zurück.

**Parameter:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| level | int |  |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Legt das Gruppierungselement für die angegebene Stufe fest.

**Parameter:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| level | int | Kategorie-Stufe int |
| value | java.lang.Object | Gruppierungselement-Objekt |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Entfernt das Gruppierungselement für die angegebene Stufe.

**Parameter:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| level | int | Kategorie-Stufe int |