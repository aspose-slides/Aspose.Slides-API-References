---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /el/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Αναπαριστά ένα βίντεο ενσωματωμένο σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ενός βίντεο, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Επιστρέφει έναν τύπο MIME ενός βίντεο, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Επιστρέφει το αντίγραφο των δεδομένων ήχου. Σε περίπτωση μεγάλης ποσότητας δεδομένων, σκεφτείτε τη χρήση της \#getStream.getStream μεθόδου για να αποφύγετε το άσκοπο φόρτωμα των δεδομένων του βίντεο στη μνήμη ή ακόμη και την εξαίρεση OutOfMemoryException. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε 'using' ή κλείστε τη ροή μετά τη χρήση.

**Επιστρέφει:**
java.io.InputStream - Stream για ανάγνωση.