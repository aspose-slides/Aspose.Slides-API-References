---
title: ITabCollection
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά μια συλλογή από στηλοθέτες.
type: docs
url: /el/com.aspose.slides/itabcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Αναπαριστά μια συλλογή από tabs.
## Μεθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [add(double position, int align)](#add-double-int-) | Προσθέτει ένα Tab στη συλλογή. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Προσθέτει ένα Tab στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο ανάγνωση [ITab](../../com.aspose.slides/itab).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Προσθέτει ένα Tab στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | double | Θέση Tab. |
| align | int | Στοίχιση Tab. |

**Επιστρέφει:**
[ITab](../../com.aspose.slides/itab) - Προστέθηκε tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Προσθέτει ένα Tab στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Το αντικείμενο Tab που θα προστεθεί στο τέλος της συλλογής. |

**Επιστρέφει:**
int - Ο δείκτης στον οποίο προστέθηκε το tab.
### clear() {#clear--}
```
public abstract void clear()
```


Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου που θα αφαιρεθεί. |