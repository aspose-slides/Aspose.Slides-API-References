---
title: CellCircularReferenceException
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Η εξαίρεση που εκτοξεύεται όταν εντοπίζονται μία ή περισσότερες κυκλικές αναφορές όπου ένας τύπος αναφέρεται στο δικό του κελί είτε άμεσα είτε έμμεσα.
type: docs
url: /el/com.aspose.slides/cellcircularreferenceexception/
---
**Κληρονομικότητα:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Η εξαίρεση που εκτοξεύεται όταν εντοπίζονται μία ή περισσότερες κυκλικές αναφορές όπου ένας τύπος αναφέρεται στο δικό του κελί είτε άμεσα είτε έμμεσα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος και κυκλική αναφορά κελιού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getReference()](#getReference--) | Αποκτά μια κυκλική αναφορά κελιού. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) με ένα συγκεκριμένο μήνυμα σφάλματος και κυκλική αναφορά κελιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | java.lang.String | Μια συμβολοσειρά που περιγράφει το σφάλμα. |
| reference | java.lang.String | Μια κυκλική αναφορά κελιού. |

### getReference() {#getReference--}
```
public final String getReference()
```


Αποκτά μια κυκλική αναφορά κελιού.

**Επιστρέφει:**
java.lang.String