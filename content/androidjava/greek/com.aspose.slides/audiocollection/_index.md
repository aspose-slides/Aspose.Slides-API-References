---
title: AudioCollection
second_title: Ανάφορα API Java για Aspose.Slides για Android
description: Αναπαριστά μια συλλογή ενσωματωμένων αρχείων ήχου.
type: docs
url: /el/com.aspose.slides/audiocollection/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Αναπαριστά μια συλλογή ενσωματωμένων αρχείων ήχου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των αρχείων ήχου στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Προσθέτει ένα αντίγραφο αρχείου ήχου από μια άλλη παρουσίαση. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από πίνακα byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει ήχους σε καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής προς νήματα). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομετρό που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```


Επιστρέφει τον αριθμό των αρχείων ήχου στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


Προσθέτει ένα αντίγραφο αρχείου ήχου από μια άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Πηγαίος ήχος. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί ο ήχος. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί βίντεο ήχου. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στην ροή. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από πίνακα byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audioData | byte[] | Bytes ήχου. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Αντιγράφει ήχους σε καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας. |
| index | int | Δείκτης. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής προς νήματα). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Επιστρέφει έναν ενομετρό που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη στη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.