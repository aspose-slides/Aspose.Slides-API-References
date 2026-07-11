---
title: PictureFillFormat
second_title: Aspose.Slides для Android через Java API
description: Представляет стиль заполнения изображением.
type: docs
url: /ru/com.aspose.slides/picturefillformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Представляет стиль заполнения изображением.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Возвращает или задает dpi, используемый для заполнения изображением. |
| [setDpi(int value)](#setDpi-int-) | Возвращает или задает dpi, используемый для заполнения изображением. |
| [getPictureFillMode()](#getPictureFillMode--) | Возвращает или задает режим заполнения изображением. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Возвращает или задает режим заполнения изображением. |
| [getPicture()](#getPicture--) | Возвращает изображение. |
| [getCropLeft()](#getCropLeft--) | Возвращает или задает количество процентов реальной ширины изображения, обрезаемых слева от картинки. |
| [setCropLeft(float value)](#setCropLeft-float-) | Возвращает или задает количество процентов реальной ширины изображения, обрезаемых слева от картинки. |
| [getCropTop()](#getCropTop--) | Возвращает или задает количество процентов реальной высоты изображения, обрезаемых сверху картинки. |
| [setCropTop(float value)](#setCropTop-float-) | Возвращает или задает количество процентов реальной высоты изображения, обрезаемых сверху картинки. |
| [getCropRight()](#getCropRight--) | Возвращает или задает количество процентов реальной ширины изображения, обрезаемых справа от картинки. |
| [setCropRight(float value)](#setCropRight-float-) | Возвращает или задает количество процентов реальной ширины изображения, обрезаемых справа от картинки. |
| [getCropBottom()](#getCropBottom--) | Возвращает или задает количество процентов реальной высоты изображения, обрезаемых снизу картинки. |
| [setCropBottom(float value)](#setCropBottom-float-) | Возвращает или задает количество процентов реальной высоты изображения, обрезаемых снизу картинки. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Удаляет обрезанные области заполнения изображения. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Возвращает или задает левый край заполняющего прямоугольника, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Возвращает или задает левый край заполняющего прямоугольника, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Возвращает или задает верхний край заполняющего прямоугольника, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Возвращает или задает верхний край заполняющего прямоугольника, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Возвращает или задает правый край заполняющего прямоугольника, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Возвращает или задает правый край заполняющего прямоугольника, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Возвращает или задает нижний край заполняющего прямоугольника, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Возвращает или задает нижний край заполняющего прямоугольника, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. |
| [getTileOffsetX()](#getTileOffsetX--) | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в пунктах. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в пунктах. |
| [getTileOffsetY()](#getTileOffsetY--) | Возвращает или задает вертикальное смещение текстуры от начала фигуры в пунктах. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Возвращает или задает вертикальное смещение текстуры от начала фигуры в пунктах. |
| [getTileScaleX()](#getTileScaleX--) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах. |
| [getTileScaleY()](#getTileScaleY--) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах. |
| [getTileAlignment()](#getTileAlignment--) | Возвращает или задает выравнивание текстуры внутри фигуры. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Возвращает или задает выравнивание текстуры внутри фигуры. |
| [getTileFlip()](#getTileFlip--) | Отразить плитку текстуры по горизонтальной, вертикальной или обеим осям. |
| [setTileFlip(int value)](#setTileFlip-int-) | Отразить плитку текстуры по горизонтальной, вертикальной или обеим осям. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getDpi() {#getDpi--}
```
public final int getDpi()
```

Возвращает или задает dpi, используемый для заполнения изображением. Чтение/запись  int .

**Возвращает:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Возвращает или задает dpi, используемый для заполнения изображением. Чтение/запись  int .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Возвращает или задает режим заполнения изображением. Чтение/запись [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Возвращает:**
int
### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Возвращает или задает режим заполнения изображением. Чтение/запись [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Возвращает изображение. Только для чтения [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Возвращает:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Возвращает или задает количество процентов реальной ширины изображения, обрезаемых слева от картинки. Чтение/запись  float .

**Возвращает:**
float
### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Возвращает или задает количество процентов реальной ширины изображения, обрезаемых слева от картинки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Возвращает или задает количество процентов реальной высоты изображения, обрезаемых сверху картинки. Чтение/запись  float .

**Возвращает:**
float
### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Возвращает или задает количество процентов реальной высоты изображения, обрезаемых сверху картинки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Возвращает или задает количество процентов реальной ширины изображения, обрезаемых справа от картинки. Чтение/запись  float .

**Возвращает:**
float
### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Возвращает или задает количество процентов реальной ширины изображения, обрезаемых справа от картинки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Возвращает или задает количество процентов реальной высоты изображения, обрезаемых снизу картинки. Чтение/запись  float .

**Возвращает:**
float
### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Возвращает или задает количество процентов реальной высоты изображения, обрезаемых снизу картинки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Удаляет обрезанные области заполнения изображения.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Получает PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Удаляет обрезанные области изображения PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращает:**
[IPPImage](../../com.aspose.slides/ippimage) - Обрезанное изображение или оригинальное изображение, если обрезка не требуется.

--------------------

Этот метод преобразует метафайлы WMF/EMF в растровое PNG-изображение с обрезкой.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Сжимает изображение, уменьшая его размер в зависимости от размеров фигуры и указанного разрешения. При желании также удаляет обрезанные области.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` метод для уменьшения размера изображения в презентации путем установки целевого разрешения и удаления обрезанных областей:
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
> Следующий пример демонстрирует, как использовать метод ```
> CompressImage
> ```
 для уменьшения размера изображения в презентации путем установки целевого разрешения и удаления обрезанных областей:
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

Возвращает или задает левый край заполняющего прямоугольника, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

Возвращает или задает левый край заполняющего прямоугольника, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

Возвращает или задает верхний край заполняющего прямоугольника, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Возвращает или задает верхний край заполняющего прямоугольника, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Возвращает или задает правый край заполняющего прямоугольника, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

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

Возвращает или задает нижний край заполняющего прямоугольника, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительный процент указывает на врезку, отрицательный — на выступ. Чтение/запись  float .

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

По умолчанию [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |