---
title: PictureFillFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει ένα στυλ γεμίσματος εικόνας.
type: docs
url: /el/com.aspose.slides/picturefillformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Αντιπροσωπεύει ένα στυλ γεμίσματος εικόνας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για να γεμίσει μια εικόνα. |
| [setDpi(int value)](#setDpi-int-) | Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για να γεμίσει μια εικόνα. |
| [getPictureFillMode()](#getPictureFillMode--) | Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. |
| [getPicture()](#getPicture--) | Επιστρέφει την εικόνα. |
| [getCropLeft()](#getCropLeft--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από αριστερά της εικόνας. |
| [setCropLeft(float value)](#setCropLeft-float-) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από αριστερά της εικόνας. |
| [getCropTop()](#getCropTop--) | Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κορυφή της εικόνας. |
| [setCropTop(float value)](#setCropTop-float-) | Επιστέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κορυφή της εικόνας. |
| [getCropRight()](#getCropRight--) | Επιστέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από δεξιά της εικόνας. |
| [setCropRight(float value)](#setCropRight-float-) | Επιστέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από δεξιά της εικόνας. |
| [getCropBottom()](#getCropBottom--) | Επιστέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. |
| [setCropBottom(float value)](#setCropBottom-float-) | Επιστέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Διαγράφει τις περικομμένες περιοχές του γεμίσματος εικόνας. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Επιστέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιβλήματος του σχήματος. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Επιστέφει ή ορίζει την αριστερή άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την αριστερή άκρη του περιβλήματος του σχήματος. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Επιστέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιβλήματος του σχήματος. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Επιστέφει ή ορίζει την επάνω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την επάνω άκρη του περιβλήματος του σχήματος. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Επιστέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιβλήματος του σχήματος. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Επιστέφει ή ορίζει τη δεξιά άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από τη δεξιά άκρη του περιβλήματος του σχήματος. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Επιστέφει ή ορίζει την κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την κάτω άκρη του περιβλήματος του σχήματος. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Επιστέφει ή ορίζει την κάτω άκρη του ορθογωνίου γεμίσματος που ορίζεται από ποσοστιαία μετατόπιση από την κάτω άκρη του περιβλήματος του σχήματος. |
| [getTileOffsetX()](#getTileOffsetX--) | Επιστέφει ή ορίζει την οριζόντια μετατόπιση της υφής από την προέλευση του σχήματος σε σημεία. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Επιστέφει ή ορίζει την οριζόντια μετατόπιση της υφής από την προέλευση του σχήματος σε σημεία. |
| [getTileOffsetY()](#getTileOffsetY--) | Επιστέφει ή ορίζει την κάθετη μετατόπιση της υφής από την προέλευση του σχήματος σε σημεία. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Επιστέφει ή ορίζει την κάθετη μετατόπιση της υφής από την προέλευση του σχήματος σε σημεία. |
| [getTileScaleX()](#getTileScaleX--) | Επιστέφει ή ορίζει την οριζόντια κλίμακα για το γέμισμα υφής ως ποσοστό. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Επιστέφει ή ορίζει την οριζόντια κλίμακα για το γέμισμα υφής ως ποσοστό. |
| [getTileScaleY()](#getTileScaleY--) | Επιστέφει ή ορίζει την κάθετη κλίμακα για το γέμισμα υφής ως ποσοστό. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Επιστέφει ή ορίζει την κάθετη κλίμακα για το γέμισμα υφής ως ποσοστό. |
| [getTileAlignment()](#getTileAlignment--) | Επιστέφει ή ορίζει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Επιστέφει ή ορίζει πώς ευθυγραμμίζεται η υφή εντός του σχήματος. |
| [getTileFlip()](#getTileFlip--) | Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. |
| [setTileFlip(int value)](#setTileFlip-int-) | Αναστρέφει το πλακίδιο υφής γύρω από τον οριζόντιο, κάθετο ή και τους δύο άξονες. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getDpi() {#getDpi--}
```
public final int getDpi()
```


Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για να γεμίσει μια εικόνα. Ανάγνωση/εγγραφή int .

**Επιστρέφει:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Επιστρέφει ή ορίζει το dpi που χρησιμοποιείται για να γεμίσει μια εικόνα. Ανάγνωση/εγγραφή int .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```


Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση/εγγραφή [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Επιστρέφει:**
int
### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```


Επιστρέφει ή ορίζει τη λειτουργία γεμίσματος εικόνας. Ανάγνωση/εγγραφή [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Επιστρέφει την εικόνα. Μόνο για ανάγνωση [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Επιστρέφει:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από αριστερά της εικόνας. Ανάγνωση/εγγραφή float .

**Επιστρέφει:**
float
### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από αριστερά της εικόνας. Ανάγνωση/εγγραφή float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κορυφή της εικόνας. Ανάγνωση/εγγραφή float .

**Επιστρέφει:**
float
### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κορυφή της εικόνας. Ανάγνωση/εγγραφή float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από δεξιά της εικόνας. Ανάγνωση/εγγραφή float .

**Επιστρέφει:**
float
### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού πλάτους της εικόνας που περικόπτεται από δεξιά της εικόνας. Ανάγνωση/εγγραφή float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```


Επιστρέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. Ανάγνωση/εγγραφή float .

**Επιστρέφει:**
float
### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```


Επιστέφει ή ορίζει το ποσοστό του πραγματικού ύψους της εικόνας που περικόπτεται από την κάτω πλευρά της εικόνας. Ανάγνωση/εγγραφή float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```


Διαγράφει τις περικομμένες περιοχές του γεμίσματος εικόνας.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Λαμβάνει το PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Διαγράφει τις περικομμένες περιοχές της εικόνας του PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage) - Περικομμένη εικόνα ή αρχική εικόνα αν το κόψιμο δεν είναι απαραίτητο.

--------------------

Αυτή η μέθοδος μετατρέπει τα μετααρχεία WMF/EMF σε raster PNG εικόνα ενώ κόβει.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```


Συμπιέζει την εικόνα μειώνοντας το μέγεθός της με βάση το μέγεθος του σχήματος και την καθορισμένη ανάλυση. Προαιρετικά, διαγράφει επίσης τις περικομμένες περιοχές.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` μέθοδος για τη μείωση του μεγέθους μιας εικόνας σε μια παρουσίαση ορίζοντας μια στοχευόμενη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
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
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Το ακόλουθο παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη μέθοδο ```
> CompressImage
> ```
 για να μειώσετε το μέγεθος μιας εικόνας σε μια παρουσίαση ορίζοντας μια στοχευόμενη ανάλυση και αφαιρώντας τις περικομμένες περιοχές:
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
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```


Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```


Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
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
public final void setTileOffsetX(float value)
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
public final float getTileOffsetY()
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
public final void setTileOffsetY(float value)
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
public final float getTileScaleX()
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
public final void setTileScaleX(float value)
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
public final float getTileScaleY()
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
public final void setTileScaleY(float value)
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
public final byte getTileAlignment()
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

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
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
public final int getTileFlip()
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
public final void setTileFlip(int value)
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