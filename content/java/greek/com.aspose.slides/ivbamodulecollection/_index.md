---
title: IVbaModuleCollection
second_title: Aspose.Slides για την αναφορά API Java
description: Αντιπροσωπεύει μια συλλογή μονάδων του έργου VBA.
type: docs
url: /el/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Αντιπροσωπεύει μια συλλογή μονάδων του έργου VBA.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στο καθορισμένο δείκτη. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Προσθέτει μια νέα κενή μονάδα στο έργο VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Αποκτά το στοιχείο στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Προσθέτει μια νέα κενή μονάδα στο έργο VBA.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της μονάδας |

**Επιστρέφει:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Προστέθηκε μονάδα.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Η μονάδα που θα αφαιρεθεί από τη συλλογή. |
