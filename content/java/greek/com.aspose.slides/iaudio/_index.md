---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /el/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Αναπαριστά ένα ενσωματωμένο αρχείο ήχου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Επιστρέφει έναν τύπο MIME ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Επιστρέφει το αντίγραφο των δεδομένων ήχου. Σε περίπτωση μεγάλης ποσότητας δεδομένων, σκεφτείτε τη χρήση της \#getStream.getStream μεθόδου ώστε να αποτρέψετε την ανεπιθύμητη φόρτωση των δεδομένων ήχου στη μνήμη ή ακόμη OutOfMemoryException. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε 'using' ή κλείστε τη ροή μετά τη χρήση.

**Επιστρέφει:**
java.io.InputStream - Ροή για ανάγνωση.