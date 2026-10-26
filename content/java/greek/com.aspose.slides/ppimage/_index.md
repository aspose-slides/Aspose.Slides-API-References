---
title: PPImage
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια εικόνα σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/ppimage/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Αναπαριστά μια εικόνα σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει το αντίγραφο των δεδομένων μιας εικόνας. |
| [getImage()](#getImage--) | Επιστρέφει το αντίγραφο μιας εικόνας. |
| [getSvgImage()](#getSvgImage--) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Αντικαθιστά δεδομένα εικόνας. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Αντικαθιστά δεδομένα εικόνας. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Αντικαθιστά δεδομένα εικόνας. |
| [getContentType()](#getContentType--) | Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο στο BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος μιας εικόνας. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας εικόνας. |
| [getX()](#getX--) | Επιστρέφει τη μετατόπιση X μιας εικόνας. |
| [getY()](#getY--) | Επιστρέφει τη μετατόπιση Y μιας εικόνας. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό hash μιας εικόνας. |
| [dispose()](#dispose--) | Αποδεσμεύει το αντικείμενο. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Επιστρέφει το αντίγραφο των δεδομένων μιας εικόνας. Μόνο για ανάγνωση  byte[] .

**Επιστρέφει:**
byte[] - Διάταξη byte
### getImage() {#getImage--}
```
public final IImage getImage()
```


Επιστρέφει το αντίγραφο μιας εικόνας. Μόνο για ανάγνωση [IImage](../../com.aspose.slides/iimage).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Αυτή η τιμή υποδεικνύει ότι αυτή η εικόνα δημιουργήθηκε από SVG.

**Επιστρέφει:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Αυτή η τιμή υποδεικνύει ότι αυτή η εικόνα δημιουργήθηκε από SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Αντικαθιστά δεδομένα εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImageData | byte[] | Τα δεδομένα της νέας εικόνας. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Αντικαθιστά δεδομένα εικόνας. Προσοχή: όταν η Image είναι metafile - θα μετατραπεί σε raster. Χρησιμοποιήστε ReplaceImage(byte[]) αντ' αυτού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Η νέα εικόνα. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Αντικαθιστά δεδομένα εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Το νέο IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο στο BinaryData (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Επιστρέφει το πλάτος μιας εικόνας. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Επιστρέφει το ύψος μιας εικόνας. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### getX() {#getX--}
```
public final int getX()
```


Επιστρέφει τη μετατόπιση X μιας εικόνας. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### getY() {#getY--}
```
public final int getY()
```


Επιστρέφει τη μετατόπιση Y μιας εικόνας. Μόνο γιαανάγνωση  int .

**Επιστρέφει:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό hash μιας εικόνας.

**Επιστρέφει:**
int - Κωδικός hash.
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει το αντικείμενο.