---
title: PictureFillFormat
second_title: Aspose.Slides Android számára a Java API hivatkozásával
description: Kép kitöltési stílust képvisel.
type: docs
url: /hu/com.aspose.slides/picturefillformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Kép kitöltési stílust képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [setDpi(int value)](#setDpi-int-) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [getPictureFillMode()](#getPictureFillMode--) | Visszaadja vagy beállítja a kép kitöltési módot. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Visszaadja vagy beállítja a kép kitöltési módot. |
| [getPicture()](#getPicture--) | Visszaadja a képet. |
| [getCropLeft()](#getCropLeft--) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. |
| [setCropLeft(float value)](#setCropLeft-float-) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. |
| [getCropTop()](#getCropTop--) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről van levágva. |
| [setCropTop(float value)](#setCropTop-float-) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről van levágva. |
| [getCropRight()](#getCropRight--) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. |
| [setCropRight(float value)](#setCropRight-float-) | Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. |
| [getCropBottom()](#getCropBottom--) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről van levágva. |
| [setCropBottom(float value)](#setCropBottom-float-) | Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről van levágva. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Törli a kitöltött kép levágott területeit. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határoló keretének bal élétől számított százalékos eltolás. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határoló keretének bal élétől számított százalékos eltolás. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határoló keretének felső élétől számított százalékos eltolás. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határoló keretének felső élétől számított százalékos eltolás. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határoló keretének jobb élétől számított százalékos eltolás. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határoló keretének jobb élétől számított százalékos eltolás. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló keretének alsó élétől számított százalékos eltolás. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határoló keretének alsó élétől számított százalékos eltolás. |
| [getTileOffsetX()](#getTileOffsetX--) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontban. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma kiindulópontjától pontban. |
| [getTileOffsetY()](#getTileOffsetY--) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulópontjától pontban. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma kiindulópontjától pontban. |
| [getTileScaleX()](#getTileScaleX--) | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Visszaadja vagy beállítja a textúra kitöltés vízszintes méretezését százalékban. |
| [getTileScaleY()](#getTileScaleY--) | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Visszaadja vagy beállítja a textúra kitöltés függőleges méretezését százalékban. |
| [getTileAlignment()](#getTileAlignment--) | Visszaadja vagy beállítja, hogy a textúra hogyan igazodik a formán belül. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Visszaadja vagy beállítja, hogy a textúra hogyan igazodik a formán belül. |
| [getTileFlip()](#getTileFlip--) | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. |
| [setTileFlip(int value)](#setTileFlip-int-) | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

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

Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Visszatér:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

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

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. Olvasás/írás float.

**Visszatér:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép bal oldaláról van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről van levágva. Olvasás/írás float.

**Visszatér:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép felső részéről van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. Olvasás/írás float.

**Visszatér:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Visszaadja vagy beállítja a valós képszélesség százalékos arányát, amely a kép jobb oldaláról van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről van levágva. Olvasás/írás float.

**Visszatér:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Visszaadja vagy beállítja a valós képmagasság százalékos arányát, amely a kép alsó részéről van levágva. Olvasás/írás float.

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
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Törli a PictureFrame kép levágott területeit
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Levágott kép vagy eredeti kép, ha a levágás nem szükséges.

--------------------

Ez a metódus WMF/EMF metafájlokat konvertál raster PNG képpé, miközben levágja őket.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metódus a kép méretének csökkentésére egy prezentációban a célfelbontás beállításával és a levágott területek eltávolításával:
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
**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Ha igaz, a metódus eltávolítja a kép levágott területeit, esetleg tovább csökkentve a méretét. |
| resolution | int | A tömörítés célfelbontása, a [PicturesCompression](../../com.aspose.slides/picturescompression) enum egyik értékeként megadva. |

--------------------

Ez a metódus megváltoztatja a kép méretét és felbontását, hasonlóan a PowerPoint „Picture Format → Compress Pictures” funkciójához. |

**Visszatér:**
boolean - Egy logikai érték, amely jelzi, hogy a kép sikeresen tömörült-e. Visszatér, ha a kép át lett méretezve vagy levágva, egyébként nem.

### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> A következő példa bemutatja, hogyan használhatja a ```
> CompressImage
> ```
 metódust egy kép méretének csökkentésére egy prezentációban a célfelbontás beállításával és a levágott területek eltávolításával:
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
>  } while {
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
... (the text appears
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

Az alapértelmezett [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |