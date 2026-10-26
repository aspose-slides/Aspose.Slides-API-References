---
title: IPictureFillFormat
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje styl výplně obrázkem.
type: docs
url: /cs/com.aspose.slides/ipicturefillformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Reprezentuje styl výplně obrázkem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDpi()](#getDpi--) | Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku. |
| [setDpi(int value)](#setDpi-int-) | Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku. |
| [getPictureFillMode()](#getPictureFillMode--) | Vrací nebo nastavuje režim výplně obrázkem. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Vrací nebo nastavuje režim výplně obrázkem. |
| [getPicture()](#getPicture--) | Vrací obrázek. |
| [getCropLeft()](#getCropLeft--) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. |
| [setCropLeft(float value)](#setCropLeft-float-) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. |
| [getCropTop()](#getCropTop--) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní strany obrázku. |
| [setCropTop(float value)](#setCropTop-float-) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní strany obrázku. |
| [getCropRight()](#getCropRight--) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. |
| [setCropRight(float value)](#setCropRight-float-) | Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. |
| [getCropBottom()](#getCropBottom--) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní strany obrázku. |
| [setCropBottom(float value)](#setCropBottom-float-) | Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní strany obrázku. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním odsazením od levého okraje ohraničujícího rámečku tvaru. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním odsazením od levého okraje ohraničujícího rámečku tvaru. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním odsazením od horního okraje ohraničujícího rámečku tvaru. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním odsazením od horního okraje ohraničujícího rámečku tvaru. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním odsazením od pravého okraje ohraničujícího rámečku tvaru. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním odsazením od pravého okraje ohraničujícího rámečku tvaru. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním odsazením od spodního okraje ohraničujícího rámečku tvaru. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním odsazením od spodního okraje ohraničujícího rámečku tvaru. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Odstraňuje oříznuté oblasti výplně obrázku. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. |
| [getTileOffsetX()](#getTileOffsetX--) | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Vrací nebo nastavuje vodorovný posun textury od počátku tvaru v bodech. |
| [getTileOffsetY()](#getTileOffsetY--) | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Vrací nebo nastavuje svislý posun textury od počátku tvaru v bodech. |
| [getTileScaleX()](#getTileScaleX--) | Vrací nebo nastavuje vodorovné měřítko výplně textury jako procento. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Vrací nebo nastavuje vodorovné měřítko výplně textury jako procento. |
| [getTileScaleY()](#getTileScaleY--) | Vrací nebo nastavuje svislé měřítko výplně textury jako procento. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Vrací nebo nastavuje svislé měřítko výplně textury jako procento. |
| [getTileAlignment()](#getTileAlignment--) | Vrací nebo nastavuje způsob zarovnání textury uvnitř tvaru. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Vrací nebo nastavuje způsob zarovnání textury uvnitř tvaru. |
| [getTileFlip()](#getTileFlip--) | Otáčí dlaždici textury kolem vodorovné, svislé nebo obou os. |
| [setTileFlip(int value)](#setTileFlip-int-) | Otáčí dlaždici textury kolem vodorovné, svislé nebo obou os. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku. Čtení/zápis int.

**Vrací:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Vrací nebo nastavuje dpi, které se používá k vyplnění obrázku. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Vrací nebo nastavuje režim výplně obrázkem. Čtení/zápis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Vrací:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Vrací nebo nastavuje režim výplně obrázkem. Čtení/zápis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Vrací obrázek. Pouze pro čtení [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Vrací:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. Čtení/zápis float.

**Vrací:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z levé strany obrázku. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní strany obrázku. Čtení/zápis float.

**Vrací:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty z horní strany obrázku. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. Čtení/zápis float.

**Vrací:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Vrací nebo nastavuje počet procent skutečné šířky obrázku, které jsou oříznuty z pravé strany obrázku. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní strany obrázku. Čtení/zápis float.

**Vrací:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Vrací nebo nastavuje počet procent skutečné výšky obrázku, které jsou oříznuty ze spodní strany obrázku. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním odsazením od levého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Vrací:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Vrací nebo nastavuje levý okraj výplňového obdélníku, který je definován procentuálním odsazením od levého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním odsazením od horního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Vrací:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Vrací nebo nastavuje horní okraj výplňového obdélníku, který je definován procentuálním odsazením od horního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním odsazením od pravého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Vrací:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Vrací nebo nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním odsazením od pravého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním odsazením od spodního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Vrací:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Vrací nebo nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním odsazením od spodního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější odsazení. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Odstraňuje oříznuté oblasti výplně obrázku.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Deletes cropped areas of the PictureFrame image
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Oříznutý obrázek nebo původní obrázek, pokud oříznutí není nutné.

--------------------

Tato metoda převádí WMF/EMF metafily na rastrový PNG obrázek a zároveň je ořezává.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Komprimuje obrázek zmenšením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metoda ke snížení velikosti obrázku v prezentaci nastavením cílového rozlišení a odstraněním oříznutých oblastí:
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
> Následující příklad ukazuje, jak použít metodu ```
> CompressImage
> ``` ke snížení velikosti obrázku v prezentaci nastavením cílového rozlišení a odstraněním oříznutých oblastí:
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
**Vrací:**
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

--------------------

Výchozí hodnota je [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |