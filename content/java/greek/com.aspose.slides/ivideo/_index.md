---
title: IVideo
second_title: Aspose.Slides για την αναφορά API Java
description: Αντιπροσωπεύει ένα βίντεο ενσωματωμένο σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Αντιπροσωπεύει ένα βίντεο ενσωματωμένο σε μια παρουσίαση.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ενός βίντεο, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. |
| [getStream()](#getStream--) | Επιστρέφει Stream stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Επιστρέφει έναν τύπο MIME ενός βίντεο, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. Σε περίπτωση μεγάλου όγκου δεδομένων, εξετάστε τη χρήση της μεθόδου \#getStream.getStream για να αποτρέψετε την ανεπιθύμητη φόρτωση των δεδομένων του βίντεο στη μνήμη ή ακόμη και OutOfMemoryException. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Επιστρέφει Stream stream για ανάγνωση. Χρησιμοποιήστε το 'using' ή κλείστε το stream μετά τη χρήση.

**Επιστρέφει:**
java.io.InputStream - Stream for reading.