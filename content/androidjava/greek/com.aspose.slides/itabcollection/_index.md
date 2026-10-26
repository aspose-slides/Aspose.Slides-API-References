---
title: ITabCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά μια συλλογή από καρτέλες.
type: docs
url: /el/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**  
com.aspose.slides.IGenericCollection  
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Αναπαριστά μια συλλογή από tabs.

## Μεθόδους

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο index. |
| [add(double position, int align)](#add-double-int-) | Προσθέτει ένα Tab στη συλλογή. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Προσθέτει ένα Tab στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο index της συλλογής. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο index. Μόνο-ανάγνωση [ITab](../../com.aspose.slides/itab).

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
int - Ο index στον οποίο προστέθηκε το tab.

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στο καθορισμένο index της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενισμένος index του στοιχείου που θα αφαιρεθεί. |