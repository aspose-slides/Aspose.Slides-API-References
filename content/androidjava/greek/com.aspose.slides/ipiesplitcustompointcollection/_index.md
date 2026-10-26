---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή σημείων που θα σχεδιαστούν στο δεύτερο πίτα ή μπάρα σε γράφημα τύπου μπάρα-σε-πίτα ή πίτα-σε-πίτα με προσαρμοσμένο διαχωρισμό.
type: docs
url: /el/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Αναπαριστά μια συλλογή σημείων που θα σχεδιαστούν στο δεύτερο πίτα ή μπάρα σε γράφημα τύπου μπάρα-σε-πίτα ή πίτα-σε-πίτα με προσαρμοσμένο διαχωρισμό.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει σημείο δεδομένων διαγράμματος με δείκτη. |
| [add(int dataPointIndex)](#add-int-) | Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [remove(int dataPointIndex)](#remove-int-) | Καταργεί το στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Επιστρέφει σημείο δεδομένων διαγράμματος με δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του σημείου δεδομένων. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Chart data point.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Καταργεί το στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς.. |