---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /el/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Διαχειριζόμενο περιέκτη των τιμών των επιπέδων κατηγορίας του διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Επιστρέφει αντικείμενο IChartDataCell για το καθορισμένο επίπεδο. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Ορίζει το στοιχείο ομαδοποίησης για το καθορισμένο επίπεδο. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Διαγράφει το στοιχείο ομαδοποίησης για το καθορισμένο επίπεδο. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Επιστρέφει αντικείμενο IChartDataCell για το καθορισμένο επίπεδο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| level | int |  |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Ορίζει το στοιχείο ομαδοποίησης για το καθορισμένο επίπεδο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| level | int | Επίπεδο κατηγορίας int |
| value | java.lang.Object | Αντικείμενο στοιχείου ομαδοποίησης |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Διαγράφει το στοιχείο ομαδοποίησης για το καθορισμένο επίπεδο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| level | int | Επίπεδο κατηγορίας int |