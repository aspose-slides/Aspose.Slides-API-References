---
title: IControlCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Μια συλλογή ελέγχων ActiveX.
type: docs
url: /el/com.aspose.slides/icontrolcollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Μια συλλογή ελέγχων ActiveX.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Αφαιρεί έναν έλεγχο ActiveX από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί έναν έλεγχο ActiveX αποθηκευμένο σε συγκεκριμένη θέση από τη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλους τους ελέγχους από τη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει έναν έλεγχο στη συγκεκριμένη θέση. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Δημιουργεί και προσθέτει ένα νέο έλεγχο στη συλλογή. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Αφαιρεί έναν έλεγχο ActiveX από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ένας έλεγχος προς αφαίρεση. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί έναν έλεγχο ActiveX αποθηκευμένο σε συγκεκριμένη θέση από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός ελέγχου προς αφαίρεση. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλους τους ελέγχους από τη συλλογή.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Επιστρέφει έναν έλεγχο στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός ελέγχου. |

**Επιστρέφει:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Δημιουργεί και προσθέτει ένα νέο έλεγχο στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlType | int | Τύπος ελέγχου προς προσθήκη. |
| x | float | Η συντεταγμένη X για την αριστερή πλευρά του πλαισίου του σχήματος. |
| y | float | Η συντεταγμένη Y για την άνω πλευρά του πλαισίου του σχήματος. |
| width | float | Το πλάτος του πλαισίου του σχήματος. |
| height | float | Το ύψος του πλαισίου του σχήματος. |

**Επιστρέφει:**
[IControl](../../com.aspose.slides/icontrol) - Δημιουργήθηκε ο έλεγχος [IControl](../../com.aspose.slides/icontrol).