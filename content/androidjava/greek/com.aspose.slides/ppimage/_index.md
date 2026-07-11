---
title: PPImage
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια εικόνα σε μια παρουσίαση.
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

Αντιπροσωπεύει μια εικόνα στην παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Επιστρέφει αντίγραφο των δεδομένων μιας εικόνας. |
| [getImage()](#getImage--) | Επιστρέφει αντίγραφο μιας εικόνας. |
| [getSvgImage()](#getSvgImage--) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Αντικαθιστά τα δεδομένα της εικόνας. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Αντικαθιστά τα δεδομένα της εικόνας. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Αντικαθιστά τα δεδομένα της εικόνας. |
| [getContentType()](#getContentType--) | Επιστρέφει τύπο MIME μιας εικόνας, κωδικοποιημένο σε BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος μιας εικόνας. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος μιας εικόνας. |
| [getX()](#getX--) | Επιστρέφει την οριζόντια μετατόπιση (X) μιας εικόνας. |
| [getY()](#getY--) | Επιστρέφει την κατακόρυφη μετατόπιση (Y) μιας εικόνας. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού μιας εικόνας. |
| [dispose()](#dispose--) | Καταστρέφει το αντικείμενο. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Επιστρέφει αντίγραφο των δεδομένων μιας εικόνας. Μόνο για ανάγνωση  byte[] .

**Επιστρέφει:**
byte[] - Πίνακας byte
### getImage() {#getImage--}
```
public final IImage getImage()
```

Επιστρέφει αντίγραφο μιας εικόνας. Μόνο για ανάγνωση [IImage](../../com.aspose.slides/iimage).

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

Αντικαθιστά τα δεδομένα της εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImageData | byte[] | Τα δεδομένα της νέας εικόνας. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Αντικαθιστά τα δεδομένα της εικόνας. Προσοχή: όταν η Image είναι metafile - θα rasterized. Χρησιμοποιήστε ReplaceImage(byte[]) αντί αυτού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Η νέα εικόνα. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Αντικαθιστά τα δεδομένα της εικόνας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Η νέα IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Επιστρέφει τύπο MIME μιας εικόνας, κωδικοποιημένο σε BinaryData (\#getBinaryData.getBinaryData). Μόνο για ανάγνωση String.

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

Επιστρέφει την οριζόντια μετατόπιση (X) μιας εικόνας. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### getY() {#getY--}
```
public final int getY()
```

Επιστρέφει την κατακόρυφη μετατόπιση (Y) μιας εικόνας. Μόνο για ανάγνωση  int .

**Επιστρέφει:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

Επιστέφει τον κωδικό κατακερματισμού μιας εικόνας.

**Επιστρέφει:**
int - Κωδικός κατακερματισμού.
### dispose() {#dispose--}
```
public final void dispose()
```

Καταστρέφει το αντικείμενο.