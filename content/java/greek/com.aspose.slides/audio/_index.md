---
title: Audio
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά ένα ενσωματωμένο αρχείο ήχου.
type: docs
url: /el/com.aspose.slides/audio/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Αναπαριστά ένα ενσωματωμένο αρχείο ήχου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων του ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). String μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο σε (\#getBinaryData.getBinaryData). String μόνο για ανάγνωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Επιστρέφει το αντίγραφο των δεδομένων του ήχου. Σε περίπτωση μεγάλου όγκου δεδομένων, εξετάστε τη χρήση της μεθόδου \#getStream.getStream για την αποφυγή περιττής φόρτωσης των δεδομένων του ήχου στη μνήμη ή ακόμη και OutOfMemoryException. Byte[] μόνο για ανάγνωση.

**Επιστρέφει:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποιήστε το 'using' ή κλείστε τη ροή μετά τη χρήση.

**Επιστρέφει:**
java.io.InputStream - Ροή για ανάγνωση.