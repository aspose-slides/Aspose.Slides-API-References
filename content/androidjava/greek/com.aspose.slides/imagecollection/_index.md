---
title: ImageCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει τη συλλογή PPImage.
type: docs
url: /el/com.aspose.slides/imagecollection/
---
**Inheritance:**  
Κληρονομικότητα: java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)  
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Represents collection of PPImage.  
Αντιπροσωπεύει τη συλλογή PPImage.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των εικόνων στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στο καθορισμένο δείκτη. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Προσθέτει αντίγραφο μιας εικόνας από άλλη παρουσίαση. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Προσθέτει μια εικόνα σε παρουσίαση. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Προσθέτει εικόνα σε παρουσίαση από ροή. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Δημιουργεί και προσθέτει εικόνα σε παρουσίαση από ροή. |
| [addImage(byte[] buffer)](#addImage-byte---) | Προσθέτει εικόνα σε παρουσίαση από το καθορισμένο buffer. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Προσθέτει εικόνα σε παρουσίαση από αντικείμενο Svg. |
| [iterator()](#iterator--) | Επιστρέφει έναν αδιακόπτη που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των εικόνων στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Επιστρέφει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IPPImage](../../com.aspose.slides/ippimage).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Προσθέτει ένα αντίγραφο εικόνας από άλλη παρουσίαση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Πηγή εικόνας. |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Η εικόνα προστέθηκε.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Προσθέτει μια εικόνα σε παρουσίαση.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα προς προσθήκη.

--------------------

Αυτή η μέθοδος μετατρέπει αρχεία metafile WMF/EMF σε raster PNG εικόνα προτού την εισάγει σε παρουσίαση. |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Η εικόνα προστέθηκε.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Προσθέτει μια εικόνα σε παρουσίαση από ροή.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί η εικόνα.

--------------------

Αυτή η μέθοδος μπορεί να προσθέσει αρχεία metafile WMF/EMF σε παρουσίαση χωρίς να τα μετατρέπει σε raster PNG εικόνα. |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Η εικόνα προστέθηκε.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει εικόνα σε παρουσίαση από ροή.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί το αρχείο εικόνας. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Προσθέτει μια εικόνα σε παρουσίαση από το καθορισμένο buffer.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Η εικόνα προστέθηκε.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Προσθέτει μια εικόνα σε παρουσίαση από αντικείμενο Svg.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Αντικείμενο εικόνας Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Επιστρέφει:**  
[IPPImage](../../com.aspose.slides/ippimage) - Η εικόνα προστέθηκε.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Επιστρέφει έναν αδιακόπτη που διατρέχει τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για τη διέλευση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας-στόχος. |
| index | int | Αρχικός δείκτης στον πίνακα-στόχο. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση  boolean .

**Επιστρέφει:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση  Object .

**Επιστρέφει:**  
java.lang.Object