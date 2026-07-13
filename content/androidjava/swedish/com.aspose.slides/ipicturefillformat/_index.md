---
title: IPictureFillFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bildfyllningsstil.
type: docs
url: /sv/com.aspose.slides/ipicturefillformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Representerar en bildfyllningsstil.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDpi()](#getDpi--) | Returnerar eller anger DPI som används för att fylla en bild. |
| [setDpi(int value)](#setDpi-int-) | Returnerar eller anger DPI som används för att fylla en bild. |
| [getPictureFillMode()](#getPictureFillMode--) | Returnerar eller anger bildfyllningsläget. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Returnerar eller anger bildfyllningsläget. |
| [getPicture()](#getPicture--) | Returnerar bilden. |
| [getCropLeft()](#getCropLeft--) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens vänstra sida. |
| [setCropLeft(float value)](#setCropLeft-float-) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens vänstra sida. |
| [getCropTop()](#getCropTop--) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens övre sida. |
| [setCropTop(float value)](#setCropTop-float-) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens övre sida. |
| [getCropRight()](#getCropRight--) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens högra sida. |
| [setCropRight(float value)](#setCropRight-float-) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens högra sida. |
| [getCropBottom()](#getCropBottom--) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens nedre sida. |
| [setCropBottom(float value)](#setCropBottom-float-) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens nedre sida. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Returnerar eller anger vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från vänsterkant av formens avgränsningsruta. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Returnerar eller anger vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från vänsterkant av formens avgränsningsruta. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Returnerar eller anger överkant av fyllningsrektangeln som definieras av en procentuell förskjutning från överkant av formens avgränsningsruta. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Returnerar eller anger överkant av fyllningsrektangeln som definieras av en procentuell förskjutning från överkant av formens avgränsningsruta. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Returnerar eller anger högerkant av fyllningsrektangeln som definieras av en procentuell förskjutning från högerkant av formens avgränsningsruta. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Returnerar eller anger högerkant av fyllningsrektangeln som definieras av en procentuell förskjutning från högerkant av formens avgränsningsruta. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Returnerar eller anger nederkant av fyllningsrektangeln som definieras av en procentuell förskjutning från nederkant av formens avgränsningsruta. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Returnerar eller anger nederkant av fyllningsrektangeln som definieras av en procentuell förskjutning från nederkant av formens avgränsningsruta. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Ta bort beskurna områden av fyllningsbilden. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. |
| [getTileOffsetX()](#getTileOffsetX--) | Returnerar eller anger horisontell förskjutning av texturen från figurens ursprung i punkter. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Returnerar eller anger horisontell förskjutning av texturen från figurens ursprung i punkter. |
| [getTileOffsetY()](#getTileOffsetY--) | Returnerar eller anger vertikal förskjutning av texturen från figurens ursprung i punkter. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Returnerar eller anger vertikal förskjutning av texturen från figurens ursprung i punkter. |
| [getTileScaleX()](#getTileScaleX--) | Returnerar eller anger horisontell skala för texturfyllnad i procent. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Returnerar eller anger horisontell skala för texturfyllnad i procent. |
| [getTileScaleY()](#getTileScaleY--) | Returnerar eller anger vertikal skala för texturfyllnad i procent. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Returnerar eller anger vertikal skala för texturfyllnad i procent. |
| [getTileAlignment()](#getTileAlignment--) | Returnerar eller anger hur texturen är justerad inom formen. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Returnerar eller anger hur texturen är justerad inom formen. |
| [getTileFlip()](#getTileFlip--) | Vänder texturplattan horisontellt, vertikalt eller på båda axlarna. |
| [setTileFlip(int value)](#setTileFlip-int-) | Vänder texturplattan horisontellt, vertikalt eller på båda axlarna. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Returnerar eller anger DPI som används för att fylla en bild. Läs/skriv int.

**Returnerar:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Returnerar eller anger DPI som används för att fylla en bild. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Returnerar eller anger bildfyllningsläget. Läs/skriv [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Returnerar:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Returnerar eller anger bildfyllningsläget. Läs/skriv [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Returnerar bilden. Skriftskyddad [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returnerar:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens vänstra sida. Läs/skriv float.

**Returnerar:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens vänstra sida. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens övre sida. Läs/skriv float.

**Returnerar:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens övre sida. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens högra sida. Läs/skriv float.

**Returnerar:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs från bildens högra sida. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens nedre sida. Läs/skriv float.

**Returnerar:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs från bildens nedre sida. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Returnerar eller anger vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från vänsterkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Returnerar:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Returnerar eller anger vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från vänsterkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Returnerar eller anger överkant av fyllningsrektangeln som definieras av en procentuell förskjutning från överkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Returnerar:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Returnerar eller anger överkant av fyllningsrektangeln som definieras av en procentuell förskjutning från överkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Returnerar eller anger högerkant av fyllningsrektangeln som definieras av en procentuell förskjutning från högerkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Returnerar:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Returnerar eller anger högerkant av fyllningsrektangeln som definieras av en procentuell förskjutning från högerkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Returnerar eller anger nederkant av fyllningsrektangeln som definieras av en procentuell förskjutning från nederkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Returnerar:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchBottom(float value)
```

Returnerar eller anger nederkant av fyllningsrektangeln som definieras av en procentuell förskjutning från nederkant av formens avgränsningsruta. En positiv procentsats anger ett inskjut, medan en negativ procentsats anger ett utskjut. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Ta bort beskurna områden av fyllningsbilden.

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Hämtar bildramen
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Tar bort beskurna områden i PictureFrame-bilden
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Beskuren bild eller originalbild om beskärning inte är nödvändig.

Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild samtidigt som den beskär.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Alternativt tar den även bort beskurna områden.

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metod för att minska storleken på en bild i en presentation genom att ange en målupplösning och ta bort beskurna områden:
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
**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Om true, kommer metoden att ta bort de beskurna områdena av bilden, vilket potentiellt ytterligare minskar dess storlek. |
| resolution | int | Måluppslagning för komprimering, specificerad som ett värde av enumen [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

Denna metod ändrar bildens storlek och upplösning på liknande sätt som PowerPoints funktion "Picture Format -> Compress Pictures" feature. |

**Returnerar:**
boolean - Ett booleskt värde som indikerar om bilden har komprimerats framgångsrikt. Returnerar true om bilden har ändrats i storlek eller beskärts, annars false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Följande exempel visar hur man använder ```
> CompressImage
> ```
- metoden för att minska storleken på en bild i en presentation genom att ange en målupplösning och ta bort beskurna områden:
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

**Returnerar:**
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
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

> Standard är [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |