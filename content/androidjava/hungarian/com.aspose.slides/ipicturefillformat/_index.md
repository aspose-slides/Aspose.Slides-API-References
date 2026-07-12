---
title: IPictureFillFormat
second_title: Aspose.Slides Android számára - Java API referencia
description: Képkitöltési stílust képvisel.
type: docs
url: /hu/com.aspose.slides/ipicturefillformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Kép kitöltési stílust képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDpi()](#getDpi--) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [setDpi(int value)](#setDpi-int-) | Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. |
| [getPictureFillMode()](#getPictureFillMode--) | Visszaadja vagy beállítja a kép kitöltési módot. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Visszaadja vagy beállítja a kép kitöltési módot. |
| [getPicture()](#getPicture--) | Visszaadja a képet. |
| [getCropLeft()](#getCropLeft--) | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldalán van levágva. |
| [setCropLeft(float value)](#setCropLeft-float-) | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldalán van levágva. |
| [getCropTop()](#getCropTop--) | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép tetejéről van levágva. |
| [setCropTop(float value)](#setCropTop-float-) | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép tetejéről van levágva. |
| [getCropRight()](#getCropRight--) | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról van levágva. |
| [setCropRight(float value)](#setCropRight-float-) | Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról van levágva. |
| [getCropBottom()](#getCropBottom--) | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép aljáról van levágva. |
| [setCropBottom(float value)](#setCropBottom-float-) | Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép aljáról van levágva. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határkeretének bal szélétől százalékos eltolással van meghatározva. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határkeretének bal szélétől százalékos eltolással van meghatározva. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határkeretének felső szélétől százalékos eltolással van meghatározva. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határkeretének felső szélétől százalékos eltolással van meghatározva. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határkeretének jobb szélétől százalékos eltolással van meghatározva. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határkeretének jobb szélétől százalékos eltolással van meghatározva. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határkeretének alsó szélétől százalékos eltolással van meghatározva. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határkeretének alsó szélétől százalékos eltolással van meghatározva. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Törli a kitöltött kép levágott területeit. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. |
| [getTileOffsetX()](#getTileOffsetX--) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredetétől pontokban. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Visszaadja vagy beállítja a textúra vízszintes eltolását a forma eredetétől pontokban. |
| [getTileOffsetY()](#getTileOffsetY--) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredetétől pontokban. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Visszaadja vagy beállítja a textúra függőleges eltolását a forma eredetétől pontokban. |
| [getTileScaleX()](#getTileScaleX--) | Visszaadja vagy beállítja a textúra vízszintes méretezését százalékban. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Visszaadja vagy beállítja a textúra vízszintes méretezését százalékban. |
| [getTileScaleY()](#getTileScaleY--) | Visszaadja vagy beállítja a textúra függőleges méretezését százalékban. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Visszaadja vagy beállítja a textúra függőleges méretezését százalékban. |
| [getTileAlignment()](#getTileAlignment--) | Visszaadja vagy beállítja, hogyan van a textúra igazítva a formában. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Visszaadja vagy beállítja, hogyan van a textúra igazítva a formában. |
| [getTileFlip()](#getTileFlip--) | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. |
| [setTileFlip(int value)](#setTileFlip-int-) | Megfordítja a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. Olvasás/írás int.

**Visszaadja:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Visszaadja vagy beállítja a képet kitöltéshez használt dpi értéket. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Visszaadja:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Visszaadja vagy beállítja a kép kitöltési módot. Olvasás/írás [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Visszaadja a képet. Csak olvasható [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Visszaadja:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldalán van levágva. Olvasás/írás float.

**Visszaadja:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldalán van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép tetejéről van levágva. Olvasás/írás float.

**Visszaadja:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép tetejéről van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról van levágva. Olvasás/írás float.

**Visszaadja:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Visszaadja vagy beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép aljáról van levágva. Olvasás/írás float.

**Visszaadja:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Visszaadja vagy beállítja a valós kép magasságának százalékos arányát, amely a kép aljáról van levágva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határkeretének bal szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Visszaadja:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Visszaadja vagy beállítja a kitöltő téglalap bal szélét, amely a forma határkeretének bal szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határkeretének felső szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Visszaadja:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Visszaadja vagy beállítja a kitöltő téglalap felső szélét, amely a forma határkeretének felső szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határkeretének jobb szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Visszaadja:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Visszaadja vagy beállítja a kitöltő téglalap jobb szélét, amely a forma határkeretének jobb szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határkeretének alsó szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Visszaadja:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Visszaadja vagy beállítja a kitöltő téglalap alsó szélét, amely a forma határkeretének alsó szélétől százalékos eltolással van meghatározva. A pozitív százalék beütemezést, a negatív pedig kiterjesztést jelent. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Törli a kitöltött kép levágott területeit.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Beszerzi a PictureFrame-et
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Törli a PictureFrame kép levágott területeit
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszaadja:**
[IPPImage](../../com.aspose.slides/ippimage) - Levágott kép vagy eredeti kép, ha a levágás nem szükséges.

--------------------

Ez a metódus WMF/EMF metafájlokat konvertál raszteres PNG képpé levágás közben.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Tömöríti a képet a méretének csökkentésével a forma mérete és a megadott felbontás alapján. Opcionálisan a levágott területeket is törli.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metódus egy kép méretének csökkentésére a prezentációban egy célfelbontás beállításával és a levágott területek eltávolításával:
>   
>   Presentation presentation = new Presentation("demo.pptx");
>   try {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>       // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>       boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
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
> A következő példa bemutatja, hogyan használható a ```
> CompressImage
> ```
 metódus egy kép méretének csökkentésére a prezentációban egy célfelbontás beállításával és a levágott területek eltávolításával:
>   
>   Presentation presentation = new Presentation("demo.pptx");
>   try {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       // Gets the PictureFrame
>       IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>       // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>       boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
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

**Parameters:
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

Az alapértelmezett [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |