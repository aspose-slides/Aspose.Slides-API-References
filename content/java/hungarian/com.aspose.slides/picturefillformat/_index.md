---
title: PictureFillFormat
second_title: Aspose.Slides Java API referencia
description: Képkitöltési stílust képvisel.
type: docs
url: /hu/com.aspose.slides/picturefillformat/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Képkitöltési stílust képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [setDpi(int value)](#setDpi-int-) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [getPictureFillMode()](#getPictureFillMode--) | Visszaadja vagy beállítja a kép kitöltési módját. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Visszaadja vagy beállítja a kép kitöltési módját. |
| [getPicture()](#getPicture--) | Visszaadja a képet. |
| [getCropLeft()](#getCropLeft--) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról le van vágva. |
| [setCropLeft(float value)](#setCropLeft-float-) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról le van vágva. |
| [getCropTop()](#getCropTop--) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről le van vágva. |
| [setCropTop(float value)](#setCropTop-float-) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről le van vágva. |
| [getCropRight()](#getCropRight--) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról le van vágva. |
| [setCropRight(float value)](#setCropRight-float-) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról le van vágva. |
| [getCropBottom()](#getCropBottom--) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről le van vágva. |
| [setCropBottom(float value)](#setCropBottom-float-) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről le van vágva. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Törli a kitöltött kép levágott területeit. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Az képet a forma mérete és a megadott felbontás alapján csökkenti, így tömörítve. Opcionálisan a levágott területeket is törli. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Az képet a forma mérete és a megadott felbontás alapján csökkenti, így tömörítve. Opcionálisan a levágott területeket is törli. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határoló dobozának bal szélétől egy százalékos eltolással van meghatározva. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határoló dobozának bal szélétől egy százalékos eltolással van meghatározva. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határoló dobozának felső szélétől egy százalékos eltolással van meghatározva. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határoló dobozának felső szélétől egy százalékos eltolással van meghatározva. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határoló dobozának jobb szélétől egy százalékos eltolással van meghatározva. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határoló dobozának jobb szélétől egy százalékos eltolással van meghatározva. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló dobozának alsó szélétől egy százalékos eltolással van meghatározva. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló dobozának alsó szélétől egy százalékos eltolással van meghatározva. |
| [getTileOffsetX()](#getTileOffsetX--) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredetétől pontban. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredetétől pontban. |
| [getTileOffsetY()](#getTileOffsetY--) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredetétől pontban. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredetétől pontban. |
| [getTileScaleX()](#getTileScaleX--) | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. |
| [getTileScaleY()](#getTileScaleY--) | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. |
| [getTileAlignment()](#getTileAlignment--) | Visszaadja vagy beállítja, hogyan van a textúra igazítva a formában. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Visszaadja vagy beállítja, hogyan van a textúra igazítva a formában. |
| [getTileFlip()](#getTileFlip--) | A textúra csempe tükrözése a vízszintes, függőleges vagy mindkét tengely mentén. |
| [setTileFlip(int value)](#setTileFlip-int-) | A textúra csempe tükrözése a vízszintes, függőleges vagy mindkét tengely mentén. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható hosszú.

**Visszatér:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. Olvasás/írás int.

**Visszatér:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Visszaadja vagy beállítja a kép kitöltési módját. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Visszatér:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Visszaadja vagy beállítja a kép kitöltési módját. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Visszaadja a képet. Csak olvasható [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Visszatér:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról le van vágva. Olvasás/írás float.

**Visszatér:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról le van vágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről le van vágva. Olvasás/írás float.

**Visszatér:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről le van vágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról le van vágva. Olvasás/írás float.

**Visszatér:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról le van vágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről le van vágva. Olvasás/írás float.

**Visszatér:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről le van vágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Törli a kitöltött kép levágott területeit.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lekéri a PictureFrame-et
>      IPictureFrame picFrame = (IPPictureFrame)slide.getShapes().get_Item(0);
>      // Törli a PictureFrame kép levágott területeit
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image or origin image if cropping is not necessary.

--------------------

Ez a metódus WMF/EMF metafájlokat raster PNG képpé konvertál, miközben levágja őket.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Az képet a forma mérete és a megadott felbontás alapján csökkenti, így tömörítve. Opcionálisan a levágott területeket is törli.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metódus egy kép méretének csökkentésére egy prezentációban célfelbontás beállításával és a levágott területek eltávolításával:
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
> The following example demonstrates how to use the ```
> CompressImage
> ```
 method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
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

Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló dobozának alsó szélétől egy százalékos eltolással van meghatározva. A pozitív százalék egy belülre helyezést, a negatív százalék pedig egy kifelé helyezést jelent. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
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

```
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
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
... (the original content cannot read
```
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
--------------------
Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
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

Alapértelmezett [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |