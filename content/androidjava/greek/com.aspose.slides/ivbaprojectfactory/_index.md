---
title: IVbaProjectFactory
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία έργου VBA μέσω COM interface
type: docs
url: /el/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Επιτρέπει τη δημιουργία έργου VBA μέσω COM interface
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Δημιουργεί νέο έργο VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Διαβάζει έργο VBA από κοντέινερ OLE. |
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

Διαβάζει έργο VBA από κοντέινερ OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Ole δεδομένα byte[] |

**Επιστρέφει:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Αναγνωσμένο έργο VBA