---
title: PictureFillFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili gaya isian gambar.
type: docs
url: /id/com.aspose.slides/picturefillformat/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Mewakili gaya isian gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. |
| [setDpi(int value)](#setDpi-int-) | Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. |
| [getPictureFillMode()](#getPictureFillMode--) | Mengembalikan atau mengatur mode isian gambar. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Mengembalikan atau mengatur mode isian gambar. |
| [getPicture()](#getPicture--) | Mengembalikan gambar. |
| [getCropLeft()](#getCropLeft--) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kiri gambar. |
| [setCropLeft(float value)](#setCropLeft-float-) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kiri gambar. |
| [getCropTop()](#getCropTop--) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian atas gambar. |
| [setCropTop(float value)](#setCropTop-float-) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian atas gambar. |
| [getCropRight()](#getCropRight--) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kanan gambar. |
| [setCropRight(float value)](#setCropRight-float-) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kanan gambar. |
| [getCropBottom()](#getCropBottom--) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. |
| [setCropBottom(float value)](#setCropBottom-float-) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Menghapus area terpotong pada Gambar isian. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Mengembalikan atau mengatur tepi kiri persegi isi yang didefinisikan oleh offset persentase dari tepi kiri kotak pembatas bentuk. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Mengembalikan atau mengatur tepi kiri persegi isi yang didefinisikan oleh offset persentase dari tepi kiri kotak pembatas bentuk. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Mengembalikan atau mengatur tepi atas persegi isi yang didefinisikan oleh offset persentase dari tepi atas kotak pembatas bentuk. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Mengembalikan atau mengatur tepi atas persegi isi yang didefinisikan oleh offset persentase dari tepi atas kotak pembatas bentuk. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Mengembalikan atau mengatur tepi kanan persegi isi yang didefinisikan oleh offset persentase dari tepi kanan kotak pembatas bentuk. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Mengembalikan atau mengatur tepi kanan persegi isi yang didefinisikan oleh offset persentase dari tepi kanan kotak pembatas bentuk. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Mengembalikan atau mengatur tepi bawah persegi isi yang didefinisikan oleh offset persentase dari tepi bawah kotak pembatas bentuk. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Mengembalikan atau mengatur tepi bawah persegi isi yang didefinisikan oleh offset persentase dari tepi bawah kotak pembatas bentuk. |
| [getTileOffsetX()](#getTileOffsetX--) | Mengembalikan atau mengatur offset horizontal tekstur dari asal bentuk dalam poin. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Mengembalikan atau mengatur offset horizontal tekstur dari asal bentuk dalam poin. |
| [getTileOffsetY()](#getTileOffsetY--) | Mengembalikan atau mengatur offset vertikal tekstur dari asal bentuk dalam poin. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Mengembalikan atau mengatur offset vertikal tekstur dari asal bentuk dalam poin. |
| [getTileScaleX()](#getTileScaleX--) | Mengembalikan atau mengatur skala horizontal untuk isian tekstur sebagai persentase. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Mengembalikan atau mengatur skala horizontal untuk isian tekstur sebagai persentase. |
| [getTileScaleY()](#getTileScaleY--) | Mengembalikan atau mengatur skala vertikal untuk isian tekstur sebagai persentase. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Mengembalikan atau mengatur skala vertikal untuk isian tekstur sebagai persentase. |
| [getTileAlignment()](#getTileAlignment--) | Mengembalikan atau mengatur cara tekstur disejajarkan dalam bentuk. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Mengembalikan atau mengatur cara tekstur disejajarkan dalam bentuk. |
| [getTileFlip()](#getTileFlip--) | Memutar ubin tekstur di sekitar sumbu horizontal, vertikal atau keduanya. |
| [setTileFlip(int value)](#setTileFlip-int-) | Memutar ubin tekstur di sekitar sumbu horizontal, vertikal atau keduanya. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. Baca/tulis int .

**Mengembalikan:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. Baca/tulis int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Mengembalikan atau mengatur mode isian gambar. Baca/tulis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Mengembalikan:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Mengembalikan atau mengatur mode isian gambar. Baca/tulis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Mengembalikan gambar. Hanya-baca [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Mengembalikan:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kiri gambar. Baca/tulis float .

**Mengembalikan:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kiri gambar. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian atas gambar. Baca/tulis float .

**Mengembalikan:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian atas gambar. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kanan gambar. Baca/tulis float .

**Mengembalikan:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong dari sisi kanan gambar. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. Baca/tulis float .

**Mengembalikan:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Menghapus area terpotong pada Gambar isian.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Mendapatkan PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Menghapus area terpotong gambar PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar terpotong atau gambar asli jika pemotongan tidak diperlukan.

--------------------

Metode ini mengonversi metafile WMF/EMF ke gambar raster PNG sambil memotong.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area terpotong.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metode untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area terpotong:
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
**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Jika true, metode ini akan menghapus area yang dipotong dari gambar, berpotensi lebih mengurangi ukurannya. |
| resolution | int | Resolusi target untuk kompresi, ditentukan sebagai nilai dari enum [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

Metode ini mengubah ukuran dan resolusi gambar serupa dengan fitur PowerPoint "Picture Format -> Compress Pictures". |

**Mengembalikan:**
boolean - Boolean yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan   jika gambar diubah ukurannya atau dipotong, sebaliknya  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Contoh berikut menunjukkan cara menggunakan metode ```
> CompressImage
> ```
 untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area terpotong:
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
Mengembalikan atau mengatur tepi kiri fill rectangle yang didefinisikan oleh offset persentase dari tepi kiri bounding box shape. Persentase positif menentukan inset, sementara persentase negatif menentukan outset. Baca/tulis float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
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

Mengembalikan atau mengatur tepi bawah fill rectangle yang didefinisikan oleh offset persentase dari tepi bawah bounding box shape. Persentase positif menentukan inset, sementara persentase negatif menentukan outset. Baca/tulis float .

**Mengembalikan:**
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

**Mengembalikan:**
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
**Parameter:**
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
**Mengembalikan:**
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
**Parameter:**
| Parameter | Tipe | Deskripsi |
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
**Mengembalikan:**
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

Default adalah [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameter:**
| Parameter | Tipe | Deskripsi |
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

Default adalah [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |