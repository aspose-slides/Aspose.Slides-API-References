---
title: VideoCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά μια συλλογή από αντικείμενα Video.
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

Αναπαριστά μια συλλογή από αντικείμενα Video.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει έναν αριθμό αρχείων βίντεο στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στο καθορισμένο δείκτη. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Προσθέτει ένα αντίγραφο αρχείου βίντεο από άλλη παρουσίαση. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από ροή. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από πίνακα byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει βίντεο σε καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει ένα στοιχείο συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει έναν αριθμό αρχείων βίντεο στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Αποκτά το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IVideo](../../com.aspose.slides/ivideo).

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

Προσθέτει ένα αντίγραφο αρχείου βίντεο από άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Πηγή βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστεθειμένο βίντεο.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προσαρτηθεί το αρχείο βίντεο. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στην ροή. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστεθειμένο [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από πίνακα byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| videoData | byte[] | Bytes βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστεθειμένο βίντεο.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει βίντεο σε καθορισμένο πίνακα ξεκινώντας από τον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας. |
| index | int | Δείκτης. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει ένα στοιχείο συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - An java.util.Iterator for the entire collection.