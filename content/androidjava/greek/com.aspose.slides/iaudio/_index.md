---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Αντιπροσωπεύει ένα ενσωματωμένο αρχείο ήχου.
type: docs
url: /el/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Αντιπροσωπεύει ένα ενσωματωμένο αρχείο ήχου.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). Μόνο-ανάγνωση String.

**Επιστρέφει:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. Σε περίπτωση μεγάλου όγκου δεδομένων, εξετάστε τη χρήση της μεθόδου \#getStream.getStream ώστε να αποφύγετε την περιττή φόρτωση των δεδομένων του ήχου στη μνήμη ή ακόμα και OutOfMemoryException. Μόνο-ανάγνωση byte[].

**Επιστρέφει:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε 'using' ή κλείστε τη ροή μετά τη χρήση.

**Επιστρέφει:**  
java.io.InputStream - Ροή για ανάγνωση.