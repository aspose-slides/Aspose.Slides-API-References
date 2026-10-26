---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά μια συλλογή σημείων που θα σχεδιαστεί στο δεύτερο κομμάτι πίτας ή μπάρας σε ένα γράφημα μπάρας-πίτας ή πίτας-πίτας με προσαρμοσμένο διαχωρισμό.
type: docs
url: /el/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Αναπαριστά μια συλλογή σημείων που θα σχεδιαστεί στο δεύτερο πίτα ή μπάρα σε ένα γράφημα μπάρας-πίτας ή πίτας-πίτας με προσαρμοσμένο διαχωρισμό.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο δεδομένων του διαγράμματος με βάση το δείκτη. |
| [add(int dataPointIndex)](#add-int-) | Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
| [remove(int dataPointIndex)](#remove-int-) | Αφαιρεί το στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Επιστρέφει το σημείο δεδομένων του διαγράμματος με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του σημείου δεδομένων. |

**Επιστροφή:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Σημείο δεδομένων του διαγράμματος.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Προσθέτει σημείο δεδομένων με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Αφαιρεί το στοιχείο από τη συλλογή με το δείκτη του στη συλλογή σημείων της γονικής σειράς.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataPointIndex | int | Δείκτης του σημείου δεδομένων στη συλλογή σημείων της γονικής σειράς.. |