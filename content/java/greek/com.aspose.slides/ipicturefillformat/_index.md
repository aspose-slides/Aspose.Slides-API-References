---
title: IPictureFillFormat
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει ένα στυλ γεμίσματος εικόνας.
type: docs
url: /el/com.aspose.slides/ipicturefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Αντιπροσωπεύει ένα στυλ γεμίσματος εικόνας.

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDpi()](#getDpi--) | Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. |
| [setDpi(int value)](#setDpi-int-) | Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. |
| [getPictureFillMode()](#getPictureFillMode--) | Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα. |
| [getCropLeft()](#getCropLeft--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. |
| [setCropLeft(float value)](#setCropLeft-float-) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. |
| [getCropTop()](#getCropTop--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την επάνω πλευρά της εικόνας. |
| [setCropTop(float value)](#setCropTop-float-) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την επάνω πλευρά της εικόνας. |
| [getCropRight()](#getCropRight--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. |
| [setCropRight(float value)](#setCropRight-float-) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. |
| [getCropBottom()](#getCropBottom--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από τη κάτω πλευρά της εικόνας. |
| [setCropBottom(float value)](#setCropBottom-float-) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από τη κάτω πλευρά της εικόνας. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Επιστρέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιοριστικού πλαισίου του σχήματος. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Επιστρέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιοριστικού πλαισίου του σχήματος. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Επιστρέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιοριστικού πλαισίου του σχήματος. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Επιστρέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιοριστικού πλαισίου του σχήματος. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Επιστρέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιοριστικού πλαισίου του σχήματος. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Επιστρέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιοριστικού πλαισίου του σχήματος. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Επιστρέφει ή ορίζει τη κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη κάτω άκρη του περιοριστικού πλαισίου του σχήματος. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Επιστρέφει ή ορίζει τη κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη κάτω άκρη του περιοριστικού πλαισίου του σχήματος. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Διαγράφει τις περικομμένες περιοχές του γεμίσματος Picture. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της βάσει του μεγέθους του σχήματος και της καθορισμένης ανάλυσης. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της βάσει του μεγέθους του σχήματος και της καθορισμένης ανάλυσης. |
| [getTileOffsetX()](#getTileOffsetX--) | Επιστρέφει ή ορίζει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες points. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Επιστρέφει ή ορίζει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες points. |
| [getTileOffsetY()](#getTileOffsetY--) | Επιστρέφει ή ορίζει την κατακόρυφη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες points. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Επιστρέφει ή ορίζει την κατακόρυφη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες points. |
| [getTileScaleX()](#getTileScaleX--) | Επιστρέφει ή ορίζει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Επιστρέφει ή ορίζει την οριζόντια κλίμακα του γεμίσματος υφής ως ποσοστό. |
| [getTileScaleY()](#getTileScaleY--) | Επιστρέφει ή ορίζει την κατακόρυφη κλίμακα του γεμίσματος υφής ως ποσοστό. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Επιστρέφει ή ορίζει την κατακόρυφη κλίμακα του γεμίσματος υφής ως ποσοστό. |
| [getTileAlignment()](#getTileAlignment--) | Επιστρέφει ή ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Επιστρέφει ή ορίζει πώς ευθυγραμμίζεται η υφή μέσα στο σχήμα. |
| [getTileFlip()](#getTileFlip--) | Αντιστρέφει το πλακάκι της υφής γύρω από τον οριζόντιο, κατακόρυφο ή και τους δύο άξονες. |
| [setTileFlip(int value)](#setTileFlip-int-) | Αντιστρέφει το πλακάκι της υφής γύρω από τον οριζόντιο, κατακόρυφο ή και τους δύο άξονες. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για το γέμισμα μιας εικόνας. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση/εγγραφή [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Επιστρέφει:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση/εγγραφή [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Επιστρέφει την εικόνα. Μόνο-ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από την αριστερή πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την επάνω πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την επάνω πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από τη δεξιά πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από τη κάτω πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από τη κάτω πλευρά της εικόνας. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Επιστρέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Επιστρέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Επιστρέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Επιστρέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Επιστρέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Επιστρέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Επιστρέφει ή ορίζει τη κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη κάτω άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Επιστρέφει ή ορίζει τη κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη κάτω άκρη του περιοριστικού πλαισίου του σχήματος. Ένα θετικό ποσοστό καθορίζει εσοχή, ενώ ένα αρνητικό ποσοστό καθορίζει έξοδο. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Διαγράφει τις περικομμένες περιοχές του γεμίσματος Picture.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Λαμβάνει το PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Διαγράφει τις περικομμένες περιοχές της εικόνας PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Περικομμένη εικόνα ή αρχική εικόνα εάν δεν απαιτείται περικοπή.

--------------------

Αυτή η μέθοδος μετατρέπει αρχεία μεταγραφής WMF/EMF σε raster PNG εικόνα ενώ περικόπτει.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Συμπιέζει την εικόνα μειώνοντας το μέγεθός της βάσει του μεγέθους του σχήματος και της καθορισμένης ανάλυσης. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` μέθοδος για τη μείωση του μεγέθους μιας εικόνας σε παρουσίαση ορίζοντας μια στοχευμένη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Το ακόλουθο παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη μέθοδο ```
> CompressImage
> ``` για τη μείωση του μεγέθους μιας εικόνας σε παρουσίαση ορίζοντας μια στοχευμένη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public abstract float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
```

Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public abstract float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Η προεπιλογή είναι [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Επιστρέφει:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public abstract void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Η προεπιλογή είναι [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |