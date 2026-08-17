---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /el/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Επιτρέπει τη δημιουργία έργου VBA μέσω διεπαφής COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Δημιουργεί νέο έργο VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Διαβάζει το έργο VBA από το κοντέινερ OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Δημιουργεί νέο έργο VBA.

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Νέο έργο VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Διαβάζει το έργο VBA από το κοντέινερ OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Δεδομένα Ole byte[] |

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Αναγνωσμένο έργο VBA