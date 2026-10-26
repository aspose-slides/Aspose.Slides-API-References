---
title: ImageCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει μια συλλογή του PPImage.
type: docs
url: /el/com.aspose.slides/imagecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Παριστάνει μια συλλογή του PPImage.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει έναν αριθμό εικόνων στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Προσθέτει μια εικόνα σε μια παρουσίαση. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Προσθέτει μια εικόνα σε μια παρουσίαση από ροή δεδομένων. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή δεδομένων. |
| [addImage(byte[] buffer)](#addImage-byte---) | Προσθέτει μια εικόνα σε μια παρουσίαση από το καθορισμένο buffer. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο Svg. |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |

### size() {#size--}
```
public final int size()
```

Επιστρέφει έναν αριθμό εικόνων στη συλλογή. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IPPImage](../../com.aspose.slides/ippimage).

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

Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Πηγή εικόνας. |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενη εικόνα.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Προσθέτει μια εικόνα σε μια παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα προς προσθήκη. |

--------------------
Αυτή η μέθοδος μετατρέπει τα αρχεία WMF/EMF σε raster PNG εικόνα πριν την εισαγωγή σε μια παρουσίαση. |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενη εικόνα.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από ροή δεδομένων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία προστίθεται η εικόνα. |

--------------------
Αυτή η μέθοδος μπορεί να προσθέσει αρχεία WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέπει σε raster PNG εικόνα. |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενη εικόνα.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή δεδομένων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία προστίθεται το αρχείο εικόνας. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενο [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από το καθορισμένο buffer.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | byte[] | Προσωρινή μνήμη. |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενη εικόνα.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο Svg.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Αντικείμενο εικόνας Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστιθέμενη εικόνα.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για να διατρέξει τη συλλογή.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Σκοπικός πίνακας. |
| index | int | Αρχικός δείκτης στον σκοπικό πίνακα. |

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