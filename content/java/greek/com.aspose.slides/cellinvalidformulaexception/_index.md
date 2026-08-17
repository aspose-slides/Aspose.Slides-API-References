---
title: CellInvalidFormulaException
second_title: Aspose.Slides για Java API Αναφορά
description: Η εξαίρεση που εκτοξεύεται όταν μια υπολογιζόμενη φόρμουλα δεν είναι σωστή ή δεν έχει αναλυθεί.
type: docs
url: /el/com.aspose.slides/cellinvalidformulaexception/
---
**Κληρονομικότητα:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Η εξαίρεση που εκτοξεύεται όταν μια υπολογιζόμενη φόρμουλα δεν είναι σωστή ή δεν έχει γίνει ανάλυση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος και αναφορά στην εσωτερική εξαίρεση που αποτελεί την αιτία αυτής της εξαίρεσης. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος και μια αναφορά κελιού που περιέχει την άκυρη φόρμουλα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getReference()](#getReference--) | Αποκτά μια αναφορά κελιού που περιέχει την άκυρη φόρμουλα. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος και αναφορά στην εσωτερική εξαίρεση που αποτελεί την αιτία αυτής της εξαίρεσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| innerException | java.lang.RuntimeException | Η εξαίρεση που αποτελεί την αιτία της τρέχουσας εξαίρεσης. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Αρχικοποιεί μια νέα παρουσία της [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) κλάσης με συγκεκριμένο μήνυμα σφάλματος και μια αναφορά κελιού που περιέχει την άκυρη φόρμουλα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| reference | java.lang.String | Μια συμβολοσειρά που περιγράφει μια αναφορά στην εσωτερική εξαίρεση |

### getReference() {#getReference--}
```
public final String getReference()
```

Αποκτά μια αναφορά κελιού που περιέχει την άκυρη φόρμουλα.

**Επιστρέφει:**
java.lang.String