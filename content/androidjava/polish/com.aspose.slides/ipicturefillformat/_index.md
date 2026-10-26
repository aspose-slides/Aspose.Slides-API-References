---
title: IPictureFillFormat
second_title: Aspose.Slides dla Androida - Referencja API Javy
description: Reprezentuje styl wypełnienia obrazem.
type: docs
url: /pl/com.aspose.slides/ipicturefillformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Reprezentuje styl wypełniania obrazem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDpi()](#getDpi--) | Zwraca lub ustawia dpi używany do wypełniania obrazu. |
| [setDpi(int value)](#setDpi-int-) | Zwraca lub ustawia dpi używany do wypełniania obrazu. |
| [getPictureFillMode()](#getPictureFillMode--) | Zwraca lub ustawia tryb wypełniania obrazem. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Zwraca lub ustawia tryb wypełniania obrazem. |
| [getPicture()](#getPicture--) | Zwraca obraz. |
| [getCropLeft()](#getCropLeft--) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po lewej stronie obrazu. |
| [setCropLeft(float value)](#setCropLeft-float-) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po lewej stronie obrazu. |
| [getCropTop()](#getCropTop--) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u góry obrazu. |
| [setCropTop(float value)](#setCropTop-float-) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u góry obrazu. |
| [getCropRight()](#getCropRight--) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po prawej stronie obrazu. |
| [setCropRight(float value)](#setCropRight-float-) | Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po prawej stronie obrazu. |
| [getCropBottom()](#getCropBottom--) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u dołu obrazu. |
| [setCropBottom(float value)](#setCropBottom-float-) | Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u dołu obrazu. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od lewej krawędzi ramki kształtu. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Zwraca lub ustawia lewą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od lewej krawędzi ramki kształtu. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Zwraca lub ustawia górną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od górnej krawędzi ramki kształtu. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Zwraca lub ustawia górną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od górnej krawędzi ramki kształtu. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od prawej krawędzi ramki kształtu. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Zwraca lub ustawia prawą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od prawej krawędzi ramki kształtu. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od dolnej krawędzi ramki kształtu. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Zwraca lub ustawia dolną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od dolnej krawędzi ramki kształtu. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Usuwa przycięte obszary wypełnienia Picture. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. |
| [getTileOffsetX()](#getTileOffsetX--) | Zwraca lub ustawia poziomy offset tekstury względem początku kształtu w punktach. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Zwraca lub ustawia poziomy offset tekstury względem początku kształtu w punktach. |
| [getTileOffsetY()](#getTileOffsetY--) | Zwraca lub ustawia pionowy offset tekstury względem początku kształtu w punktach. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Zwraca lub ustawia pionowy offset tekstury względem początku kształtu w punktach. |
| [getTileScaleX()](#getTileScaleX--) | Zwraca lub ustawia poziomą skalę wypełnienia teksturą w procentach. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Zwraca lub ustawia poziomą skalę wypełnienia teksturą w procentach. |
| [getTileScaleY()](#getTileScaleY--) | Zwraca lub ustawia pionową skalę wypełnienia teksturą w procentach. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Zwraca lub ustawia pionową skalę wypełnienia teksturą w procentach. |
| [getTileAlignment()](#getTileAlignment--) | Zwraca lub ustawia sposób wyrównania tekstury wewnątrz kształtu. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Zwraca lub ustawia sposób wyrównania tekstury wewnątrz kształtu. |
| [getTileFlip()](#getTileFlip--) | Odwraca kafelek tekstury wokół jego osi poziomej, pionowej lub obu. |
| [setTileFlip(int value)](#setTileFlip-int-) | Odwraca kafelek tekstury wokół jego osi poziomej, pionowej lub obu. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Zwraca lub ustawia dpi używany do wypełniania obrazu. Odczyt/zapis int.

**Zwraca:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Zwraca lub ustawia dpi używany do wypełniania obrazu. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Zwraca lub ustawia tryb wypełniania obrazem. Odczyt/zapis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Zwraca:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Zwraca lub ustawia tryb wypełniania obrazem. Odczyt/zapis [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Zwraca obraz. Tylko odczyt [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Zwraca:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po lewej stronie obrazu. Odczyt/zapis float.

**Zwraca:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po lewej stronie obrazu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u góry obrazu. Odczyt/zapis float.

**Zwraca:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u góry obrazu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po prawej stronie obrazu. Odczyt/zapis float.

**Zwraca:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Zwraca lub ustawia liczbę procent rzeczywistej szerokości obrazu, które są przycięte po prawej stronie obrazu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u dołu obrazu. Odczyt/zapis float.

**Zwraca:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Zwraca lub ustawia liczbę procent rzeczywistej wysokości obrazu, które są przycięte u dołu obrazu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Zwraca lub ustawia lewą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od lewej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Zwraca:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Zwraca lub ustawia lewą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od lewej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Zwraca lub ustawia górną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od górnej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Zwraca:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Zwraca lub ustawia górną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od górnej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Zwraca lub ustawia prawą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od prawej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Zwraca:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Zwraca lub ustawia prawą krawędź prostokąta wypełnienia definiowaną przez procentowy offset od prawej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Zwraca lub ustawia dolną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od dolnej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Zwraca:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Zwraca lub ustawia dolną krawędź prostokąta wypełnienia definiowaną przez procentowy offset od dolnej krawędzi ramki kształtu. Pozytywny procent określa wcięcie, natomiast negatywny procent określa występ. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Usuwa przycięte obszary wypełnienia Picture.

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Pobiera PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Usuwa przycięte obszary obrazu PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage) - Obcięty obraz lub oryginalny obraz, jeśli przycinanie nie jest konieczne.

Ta metoda konwertuje pliki metafile WMF/EMF na rastrowy obraz PNG podczas przycinania.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa przycięte obszary.

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metoda do zmniejszenia rozmiaru obrazu w prezentacji poprzez ustawienie docelowej rozdzielczości i usunięcie przyciętych obszarów:
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
> Poniższy przykład pokazuje, jak użyć metody ```
> CompressImage
> ``` do zmniejszenia rozmiaru obrazu w prezentacji poprzez ustawienie docelowej rozdzielczości i usunięcie przyciętych obszarów:
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

**Parameters:
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:
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

**Zwraca:**
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
>  } while {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
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

**Zwraca:**
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

Domyślnie jest [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |