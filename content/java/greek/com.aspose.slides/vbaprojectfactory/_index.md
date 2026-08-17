---
title: VbaProjectFactory
second_title: Aspose.Slides για την τεκμηρίωση API Java
description: Επιτρέπει τη δημιουργία έργου VBA μέσω διεπαφής COM
type: docs
url: /el/com.aspose.slides/vbaprojectfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Επιτρέπει τη δημιουργία έργου VBA μέσω διεπαφής COM
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInstance()](#getInstance--) | Στατική παρουσία εργοστασίου VBA. |
| [createVbaProject()](#createVbaProject--) | Δημιουργεί νέο έργο VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Στατική παρουσία εργοστασίου VBA. Μόνο για ανάγνωση [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Επιστρέφει:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Δημιουργεί νέο έργο VBA.

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Νέο έργο VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Αναγιγνεί έργο VBA από το δοχείο OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] |  |

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Έργο VBA που διαβάστηκε