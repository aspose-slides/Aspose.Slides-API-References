---
title: CellInvalidFormulaException
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Η εξαίρεση που προκαλείται όταν ένας υπολογισμένος τύπος δεν είναι σωστός ή δεν έχει αναλυθεί.
type: docs
url: /el/com.aspose.slides/cellinvalidformulaexception/
---
**Κληρονομικότητα:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Η εξαίρεση που προκαλείται όταν ένας υπολογισμένος τύπος δεν είναι σωστός ή δεν έχει αναλυθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά κελιού που περιέχει τον μη έγκυρο τύπο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getReference()](#getReference--) | Λαμβάνει μια αναφορά κελιού που περιέχει τον μη έγκυρο τύπο. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μία συμβολοσειρά που περιγράφει το σφάλμα. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μία συμβολοσειρά που περιγράφει το σφάλμα. |
| innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) με ένα καθορισμένο μήνυμα σφάλματος και μια αναφορά κελιού που περιέχει τον μη έγκυρο τύπο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μία συμβολοσειρά που περιγράφει το σφάλμα. |
| reference | java.lang.String | Μία συμβολοσειρά που περιγράφει μια αναφορά στην εσωτερική εξαίρεση |

### getReference() {#getReference--}
```
public final String getReference()
```


Λαμβάνει μια αναφορά κελιού που περιέχει τον μη έγκυρο τύπο.

**Επιστρέφει:**
java.lang.String