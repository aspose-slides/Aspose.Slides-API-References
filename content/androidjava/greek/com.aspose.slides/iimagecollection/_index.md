---
title: IImageCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τη συλλογή των PPImage.
type: docs
url: /el/com.aspose.slides/iimagecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**  
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Αντιπροσωπεύει τη συλλογή των PPImage.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει εικόνα με το δείκτη της. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Προσθέτει μια εικόνα σε μια παρουσίαση. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Προσθέτει μια εικόνα σε μια παρουσίαση από ροή. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή. |
| [addImage(byte[] buffer)](#addImage-byte---) | Προσθέτει μια εικόνα σε μια παρουσίαση από καθορισμένο buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Επιστρέφει εικόνα με το δείκτη της.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Προσθέτει μια εικόνα σε μια παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα προς προσθήκη.

--------------------

Αυτή η μέθοδος μετατρέπει τα αρχεία μεταγραφής WMF/EMF σε raster PNG εικόνα πριν την εισαγωγή σε παρουσίαση. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε εικόνα.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί η εικόνα.

--------------------

Αυτή η μέθοδος μπορεί να προσθέσει αρχεία μεταγραφής WMF/EMF σε μια παρουσίαση χωρίς να τα μετατρέψει σε raster PNG εικόνα. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε εικόνα.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει μια εικόνα σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί το αρχείο εικόνας. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από καθορισμένο buffer.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | byte[] | Περιέκτης. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε εικόνα.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Προσθέτει ένα αντίγραφο μιας εικόνας από μια άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Πηγή εικόνας. |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε εικόνα.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Προσθέτει μια εικόνα σε μια παρουσίαση από αντικείμενο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Αντικείμενο εικόνας SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Επιστροφή:**
[IPPImage](../../com.aspose.slides/ippimage) - Προστέθηκε εικόνα.