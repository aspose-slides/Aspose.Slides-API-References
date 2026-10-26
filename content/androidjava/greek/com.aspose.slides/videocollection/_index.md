---
title: VideoCollection
second_title: Aspose.Slides για Android μέσω Java Αναφορά API
description: Αναπαριστά μια συλλογή αντικειμένων Video.
type: docs
url: /el/com.aspose.slides/videocollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Αναπαριστά μια συλλογή αντικειμένων Video.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει αριθμό αρχείων βίντεο στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στην καθορισμένη θέση. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Προσθέτει αντίγραφο ενός αρχείου βίντεο από μια άλλη παρουσίαση. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από ροή. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει βίντεο σε καθορισμένο πίνακα ξεκινώντας από την καθορισμένη θέση. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νημάτων). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει αριθμό αρχείων βίντεο στη συλλογή. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Αποκτά το στοιχείο στην καθορισμένη θέση. Μόνο-ανάγνωση [IVideo](../../com.aspose.slides/ivideo).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Προσθέτει αντίγραφο ενός αρχείου βίντεο από μια άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Πηγή βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστέθηκε βίντεο.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί το αρχείο βίντεο. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστέθηκε [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από πίνακα byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| videoData | byte[] | Bytes του βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστέθηκε βίντεο.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει βίντεο σε καθορισμένο πίνακα ξεκινώντας από την καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας. |
| index | int | Θέση. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής-νημάτων). Μόνο-ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο-ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ένα IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διατρέξει τη συλλογή.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.