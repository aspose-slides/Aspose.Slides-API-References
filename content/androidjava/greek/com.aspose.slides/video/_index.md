---
title: Video
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά μια εικόνα ενσωματωμένη σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/video/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Αναπαριστά μια εικόνα ενσωματωμένη σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME βίντεο, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Επιστρέφει έναν τύπο MIME βίντεο, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Επιστρέφει το αντίγραφο των δεδομένων ήχου. Σε περίπτωση μεγάλης ποσότητας δεδομένων, σκεφτείτε τη χρήση της μεθόδου \#getStream.getStream για να αποτρέψετε την άσκοπη φόρτωση των δεδομένων βίντεο στη μνήμη ή ακόμη και OutOfMemoryException. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε 'using' ή κλείστε τη ροή μετά τη χρήση.

**Επιστρέφει:**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject