---
title: CellInvalidReferenceException
second_title: Αναφορά API του Aspose.Slides για Java
description: Η εξαίρεση που προκαλείται όταν εντοπίζεται μη έγκυρη αναφορά κελιού.
type: docs
url: /el/com.aspose.slides/cellinvalidreferenceexception/
---
**Κληρονομικότητα:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Η εξαίρεση που προκαλείται όταν εντοπίζεται μη έγκυρη αναφορά κελιού.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος και μια μη έγκυρη αναφορά κελιού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getReference()](#getReference--) | Λαμβάνει μια μη έγκυρη αναφορά κελιού. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα καθορισμένο μήνυμα σφάλματος και μια μη έγκυρη αναφορά κελιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| reference | java.lang.String | Μια μη έγκυρη αναφορά κελιού. |

### getReference() {#getReference--}
```
public final String getReference()
```

Λαμβάνει μια μη έγκυρη αναφορά κελιού.

**Επιστρέφει:**
java.lang.String