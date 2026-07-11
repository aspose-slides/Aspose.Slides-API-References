---
title: IVbaReferenceFactory
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία αναφορών έργου VBA μέσω διεπαφής COM
type: docs
url: /el/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Επιτρέπει τη δημιουργία αναφορών έργου VBA μέσω διεπαφής COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Δημιουργεί νέα αναφορά βιβλιοθήκης τύπου OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Δημιουργεί νέα αναφορά βιβλιοθήκης τύπου OLE Automation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της αναφοράς έργου VBA String |
| libid | java.lang.String | Αναγνωριστικό μιας βιβλιοθήκης τύπου Automation String |

**Επιστρέφει:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Νέα αναφορά βιβλιοθήκης τύπου OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)