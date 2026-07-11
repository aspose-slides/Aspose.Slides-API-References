---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Παριστάνει μια εικόνα σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Παριστάνει μια εικόνα σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων μιας εικόνας. |
| [getImage()](#getImage--) | Επιστρέφει το αντίγραφο μιας εικόνας. |
| [getSvgImage()](#getSvgImage--) | Επιστρέφει ή θέτει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Επιστρέφει ή θέτει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Αντικαθιστά τα δεδομένα της εικόνας. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Αντικαθιστά την εικόνα. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Αντικαθιστά την εικόνα. |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο στο \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος μιας εικόνας. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας εικόνας. |
| [getX()](#getX--) | Επιστρέφει την οριζόντια μετατόπιση (X) μιας εικόνας. |
| [getY()](#getY--) | Επιστρέφει την κάθετη μετατόπιση (Y) μιας εικόνας. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Επιστρέφει το αντίγραφο των δεδομένων μιας εικόνας. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Επιστρέφει το αντίγραφο μιας εικόνας. Μόνο για ανάγνωση \#getImage.getImage.

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Επιστρέφει ή θέτει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Αυτή η τιμή υποδεικνύει ότι η εικόνα δημιουργήθηκε από SVG.

**Επιστρέφει:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Επιστρέφει ή θέτει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Αυτή η τιμή υποδεικνύει ότι η εικόνα δημιουργήθηκε από SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Αντικαθιστά τα δεδομένα της εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImageData | byte[] | Τα δεδομένα της νέας εικόνας. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Αντικαθιστά την εικόνα. Προσοχή: όταν η Image είναι μετααρχείο - θα γίνει rasterized. Χρησιμοποιήστε replaceImage(byte[]) αντί αυτού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Η νέα εικόνα. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Αντικαθιστά την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Το νέο IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο στο \#getBinaryData.getBinaryData. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Επιστρέφει το πλάτος μιας εικόνας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Επιστρέφει το ύψος μιας εικόνας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Επιστρέφει την οριζόντια μετατόπιση (X) μιας εικόνας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Επιστρέφει την κάθετη μετατόπιση (Y) μιας εικόνας. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int