---
title: Audio
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα ενσωματωμένο αρχείο ήχου.
type: docs
url: /el/com.aspose.slides/audio/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Represents an embedded audio file.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. |
| [getStream()](#getStream--) | Επιστρέφει ροή Stream για ανάγνωση. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Επιστρέφει έναν τύπο MIME ενός ήχου, κωδικοποιημένο στο (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Επιστρέφει το αντίγραφο των δεδομένων ενός ήχου. Σε περίπτωση μεγάλου όγκου δεδομένων, σκεφτείτε τη χρήση της \#getStream.getStream μεθόδου για να αποφύγετε το περιττό φόρτωμα των δεδομένων ήχου στη μνήμη ή ακόμη και OutOfMemoryException. Μόνο για ανάγνωση byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Επιστρέφει ροή Stream για ανάγνωση. Χρησιμοποίηστε 'using' ή κλείστε τη ροή μετά τη χρήση.

**Returns:**
java.io.InputStream - Stream για ανάγνωση.