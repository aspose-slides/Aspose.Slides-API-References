---
title: VbaReferenceFactory
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Επιτρέπει τη δημιουργία αναφορών έργου VBA μέσω διεπαφής COM
type: docs
url: /el/com.aspose.slides/vbareferencefactory/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Επιτρέπει τη δημιουργία αναφορών έργου VBA μέσω της διεπαφής COM.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInstance()](#getInstance--) | Στατική παρουσία εργοστασίου αναφορών έργου VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Δημιουργεί νέα αναφορά βιβλιοθήκης τύπου OLE Automation. |

### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```

### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

Στατική παρουσία εργοστασίου αναφορών έργου VBA. Μόνο για ανάγνωση [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Επιστρέφει:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)

### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Δημιουργεί νέα αναφορά βιβλιοθήκης τύπου OLE Automation.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Επιστρέφει:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Νέα αναφορά βιβλιοθήκης τύπου OLE Automation