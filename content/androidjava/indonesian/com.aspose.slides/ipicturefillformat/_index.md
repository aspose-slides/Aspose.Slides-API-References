---
title: IPictureFillFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili gaya isi gambar.
type: docs
url: /id/com.aspose.slides/ipicturefillformat/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Mewakili gaya isi gambar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDpi()](#getDpi--) | Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. |
| [setDpi(int value)](#setDpi-int-) | Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. |
| [getPictureFillMode()](#getPictureFillMode--) | Mengembalikan atau mengatur mode isi gambar. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Mengembalikan atau mengatur mode isi gambar. |
| [getPicture()](#getPicture--) | Mengembalikan gambar. |
| [getCropLeft()](#getCropLeft--) | Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kiri gambar. |
| [setCropLeft(float value)](#setCropLeft-float-) | Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kiri gambar. |
| [getCropTop()](#getCropTop--) | Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian atas gambar. |
| [setCropTop(float value)](#setCropTop-float-) | Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian atas gambar. |
| [getCropRight()](#getCropRight--) | Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kanan gambar. |
| [setCropRight(float value)](#setCropRight-float-) | Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kanan gambar. |
| [getCropBottom()](#getCropBottom--) | Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian bawah gambar. |
| [setCropBottom(float value)](#setCropBottom-float-) | Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian bawah gambar. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Mengembalikan atau mengatur tepi kiri persegi panjang isi yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas shape. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Mengembalikan atau mengatur tepi kiri persegi panjang isi yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas shape. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Mengembalikan atau mengatur tepi atas persegi panjang isi yang ditentukan oleh offset persentase dari tepi atas kotak pembatas shape. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Mengembalikan atau mengatur tepi atas persegi panjang isi yang ditentukan oleh offset persentase dari tepi atas kotak pembatas shape. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Mengembalikan atau mengatur tepi kanan persegi panjang isi yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas shape. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Mengembalikan atau mengatur tepi kanan persegi panjang isi yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas shape. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Mengembalikan atau mengatur tepi bawah persegi panjang isi yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas shape. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Mengembalikan atau mengatur tepi bawah persegi panjang isi yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas shape. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Menghapus area yang dipotong dari Gambar isi. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran shape dan resolusi yang ditentukan. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran shape dan resolusi yang ditentukan. |
| [getTileOffsetX()](#getTileOffsetX--) | Mengembalikan atau mengatur offset horizontal tekstur dari origin shape dalam poin. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Mengembalikan atau mengatur offset horizontal tekstur dari origin shape dalam poin. |
| [getTileOffsetY()](#getTileOffsetY--) | Mengembalikan atau mengatur offset vertikal tekstur dari origin shape dalam poin. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Mengembalikan atau mengatur offset vertikal tekstur dari origin shape dalam poin. |
| [getTileScaleX()](#getTileScaleX--) | Mengembalikan atau mengatur skala horizontal untuk isi tekstur sebagai persentase. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Mengembalikan atau mengatur skala horizontal untuk isi tekstur sebagai persentase. |
| [getTileScaleY()](#getTileScaleY--) | Mengembalikan atau mengatur skala vertikal untuk isi tekstur sebagai persentase. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Mengembalikan atau mengatur skala vertikal untuk isi tekstur sebagai persentase. |
| [getTileAlignment()](#getTileAlignment--) | Mengembalikan atau mengatur cara tekstur disejajarkan di dalam shape. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Mengembalikan atau mengatur cara tekstur disejajarkan di dalam shape. |
| [getTileFlip()](#getTileFlip--) | Membalik ubin tekstur secara horizontal, vertikal, atau kedua sumbu. |
| [setTileFlip(int value)](#setTileFlip-int-) | Membalik ubin tekstur secara horizontal, vertikal, atau kedua sumbu. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. Baca/tulis int.

**Mengembalikan:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Mengembalikan atau mengatur mode isi gambar. Baca/tulis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Mengembalikan:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Mengembalikan atau mengatur mode isi gambar. Baca/tulis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Mengembalikan gambar. Baca-saja [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Mengembalikan:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kiri gambar. Baca/tulis float.

**Mengembalikan:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kiri gambar. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian atas gambar. Baca/tulis float.

**Mengembalikan:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian atas gambar. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kanan gambar. Baca/tulis float.

**Mengembalikan:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Mengembalikan atau mengatur persentase lebar gambar nyata yang dipotong di sisi kanan gambar. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian bawah gambar. Baca/tulis float.

**Mengembalikan:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Mengembalikan atau mengatur persentase tinggi gambar nyata yang dipotong di bagian bawah gambar. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Mengembalikan atau mengatur tepi kiri persegi panjang isi yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Mengembalikan:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Mengembalikan atau mengatur tepi kiri persegi panjang isi yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Mengembalikan atau mengatur tepi atas persegi panjang isi yang ditentukan oleh offset persentase dari tepi atas kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Mengembalikan:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Mengembalikan atau mengatur tepi atas persegi panjang isi yang ditentukan oleh offset persentase dari tepi atas kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Mengembalikan atau mengatur tepi kanan persegi panjang isi yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Mengembalikan:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Mengembalikan atau mengatur tepi kanan persegi panjang isi yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Mengembalikan atau mengatur tepi bawah persegi panjang isi yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Mengembalikan:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Mengembalikan atau mengatur tepi bawah persegi panjang isi yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas shape. Persentase positif menunjukkan inset, negatif menunjukkan outset. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Menghapus area yang dipotong dari Gambar isi.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Mendapatkan PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Menghapus area yang dipotong dari gambar PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage) - Gambar yang dipotong atau gambar asli jika pemotongan tidak diperlukan.

--------------------

Metode ini mengonversi file metafile WMF/EMF ke gambar PNG raster sambil memotong.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran shape dan resolusi yang ditentukan. Opsional, juga menghapus area yang dipotong.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metode untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong:
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
> Contoh berikut menunjukkan cara menggunakan metode ```
> CompressImage
> ```
 untuk mengurangi ukuran gambar dalam presentasi dengan menetapkan resolusi target dan menghapus area yang dipotong:
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

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
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

Default adalah [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |