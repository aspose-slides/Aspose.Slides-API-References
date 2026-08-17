---
title: AudioCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή ενσωματωμένων αρχείων ήχου.
type: docs
url: /el/com.aspose.slides/audiocollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Αντιπροσωπεύει μια συλλογή ενσωματωμένων αρχείων ήχου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει έναν αριθμό αρχείων ήχου στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Προσθέτει ένα αντίγραφο αρχείου ήχου από άλλη παρουσίαση. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από ροή. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από ροή. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από πίνακα byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ήχους στον καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει έναν αριθμό αρχείων ήχου στη συλλογή. Μόνο ανάγνωση int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο ανάγνωση [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Προσθέτει ένα αντίγραφο αρχείου ήχου από άλλη παρουσίαση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Πηγαίος ήχος. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί ο ήχος. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί ο ήχος. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Δημιουργεί και προσθέτει έναν ήχο σε μια παρουσίαση από πίνακα byte.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audioData | byte[] | Bytes ήχου. |

**Returns:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει ήχους στον καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας. |
| index | int | Δείκτης. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο ανάγνωση boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο ανάγνωση Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.