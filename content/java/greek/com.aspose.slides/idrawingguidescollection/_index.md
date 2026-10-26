---
title: IDrawingGuidesCollection
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά μια συλλογή από τις ρυθμιζόμενες οδηγίες σχεδίασης.
type: docs
url: /el/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Αναπαριστά μια συλλογή από τις ρυθμιζόμενες οδηγίες σχεδίασης.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει την οδηγία σχεδίασης με βάση το δείκτη. |
| [add(byte orientation, float position)](#add-byte-float-) | Προσθέτει την οδηγία σχεδίασης στο τέλος της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την οδηγία σχεδίασης στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Επιστρέφει την οδηγία σχεδίασης με βάση το δείκτη. Μόνο για ανάγνωση [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Προσθέτει την οδηγία σχεδίασης στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientation | byte | Προσανατολισμός της οδηγίας σχεδίασης. |
| position | float | Θέση της οδηγίας σχεδίασης σε σημεία. |

**Επιστρέφει:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την οδηγία σχεδίασης στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της οδηγίας σχεδίασης που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό όλων των στοιχείων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int