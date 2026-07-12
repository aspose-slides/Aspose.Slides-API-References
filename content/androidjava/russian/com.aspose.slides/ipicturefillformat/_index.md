---
title: IPictureFillFormat
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет стиль заполнения картинкой.
type: docs
url: /ru/com.aspose.slides/ipicturefillformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Представляет стиль заполнения картинкой.
## Методы

| Метод | Описание |
| --- | --- |
| [getDpi()](#getDpi--) | Возвращает или задает значение dpi, которое используется для заполнения изображения. |
| [setDpi(int value)](#setDpi-int-) | Возвращает или задает значение dpi, которое используется для заполнения изображения. |
| [getPictureFillMode()](#getPictureFillMode--) | Возвращает или задает режим заполнения картинкой. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Возвращает или задает режим заполнения картинкой. |
| [getPicture()](#getPicture--) | Возвращает изображение. |
| [getCropLeft()](#getCropLeft--) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано слева. |
| [setCropLeft(float value)](#setCropLeft-float-) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано слева. |
| [getCropTop()](#getCropTop--) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано сверху. |
| [setCropTop(float value)](#setCropTop-float-) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано сверху. |
| [getCropRight()](#getCropRight--) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано справа. |
| [setCropRight(float value)](#setCropRight-float-) | Возвращает или задает количество процентов реальной ширины изображения, которое обрезано справа. |
| [getCropBottom()](#getCropBottom--) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано снизу. |
| [setCropBottom(float value)](#setCropBottom-float-) | Возвращает или задает количество процентов реальной высоты изображения, которое обрезано снизу. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Возвращает или задает левый край прямоугольника заполнения, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Возвращает или задает левый край прямоугольника заполнения, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Возвращает или задает верхний край прямоугольника заполнения, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Возвращает или задает верхний край прямоугольника заполнения, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Возвращает или задает правый край прямоугольника заполнения, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Возвращает или задает правый край прямоугольника заполнения, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Возвращает или задает нижний край прямоугольника заполнения, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Возвращает или задает нижний край прямоугольника заполнения, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Удаляет обрезанные области изображения заполнения. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. |
| [getTileOffsetX()](#getTileOffsetX--) | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в точках. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Возвращает или задает горизонтальное смещение текстуры от начала фигуры в точках. |
| [getTileOffsetY()](#getTileOffsetY--) | Возвращает или задает вертикальное смещение текстуры от начала фигуры в точках. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Возвращает или задает вертикальное смещение текстуры от начала фигуры в точках. |
| [getTileScaleX()](#getTileScaleX--) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Возвращает или задает горизонтальный масштаб заполнения текстурой в процентах. |
| [getTileScaleY()](#getTileScaleY--) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Возвращает или задает вертикальный масштаб заполнения текстурой в процентах. |
| [getTileAlignment()](#getTileAlignment--) | Возвращает или задает выравнивание текстуры внутри фигуры. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Возвращает или задает выравнивание текстуры внутри фигуры. |
| [getTileFlip()](#getTileFlip--) | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям. |
| [setTileFlip(int value)](#setTileFlip-int-) | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Возвращает или задает значение dpi, которое используется для заполнения изображения. Чтение/запись int.

**Возвращает:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Возвращает или задает значение dpi, которое используется для заполнения изображения. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Возвращает или задает режим заполнения картинкой. Чтение/запись [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Возвращает:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Возвращает или задает режим заполнения картинкой. Чтение/запись [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Возвращает изображение. Только чтение [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Возвращает:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Возвращает или задает количество процентов реальной ширины изображения, которое обрезано слева. Чтение/запись float.

**Возвращает:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Возвращает или задает количество процентов реальной ширины изображения, которое обрезано слева. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Возвращает или задает количество процентов реальной высоты изображения, которое обрезано сверху. Чтение/запись float.

**Возвращает:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Возвращает или задает количество процентов реальной высоты изображения, которое обрезано сверху. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Возвращает или задает количество процентов реальной ширины изображения, которое обрезано справа. Чтение/запись float.

**Возвращает:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Возвращает или задает количество процентов реальной ширины изображения, которое обрезано справа. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Возвращает или задает количество процентов реальной высоты изображения, которое обрезано снизу. Чтение/запись float.

**Возвращает:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Возвращает или задает количество процентов реальной высоты изображения, которое обрезано снизу. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Возвращает или задает левый край прямоугольника заполнения, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Возвращает:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Возвращает или задает левый край прямоугольника заполнения, определяемый процентным смещением от левого края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Возвращает или задает верхний край прямоугольника заполнения, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Возвращает:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Возвращает или задает верхний край прямоугольника заполнения, определяемый процентным смещением от верхнего края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Возвращает или задает правый край прямоугольника заполнения, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Возвращает:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Возвращает или задает правый край прямоугольника заполнения, определяемый процентным смещением от правого края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Возвращает или задает нижний край прямоугольника заполнения, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Возвращает:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Возвращает или задает нижний край прямоугольника заполнения, определяемый процентным смещением от нижнего края ограничивающего прямоугольника фигуры. Положительный процент задает врезку, отрицательный – выступ. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Удаляет обрезанные области изображения заполнения.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Получает объект PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Удаляет обрезанные области изображения PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Возвращает:** [IPPImage](../../com.aspose.slides/ippimage) - Обрезанное изображение или исходное изображение, если обрезка не требуется.

--------------------

Этот метод преобразует метафайлы WMF/EMF в растровый PNG, одновременно обрезая их.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` метод для уменьшения размера изображения в презентации путём установки целевого разрешения и удаления обрезанных областей:
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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Если true, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | int | Целевая разрешающая способность для сжатия, указанная как значение перечисления [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

Этот метод изменяет размер и разрешение изображения аналогично функции PowerPoint "Picture Format -> Compress Pictures". |

**Возвращаемое значение:**
boolean - Булево значение, указывающее, было ли изображение успешно сжато. Возвращает true, если изображение было изменено по размеру или обрезано, иначе false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```

Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
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
**Параметры:**
| Параметр | Тип | Описание |
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
>  } while {
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
**Параметры:**
| Параметр | Тип | Описание |
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
>  } while {
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
>  } while {
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
>  } while {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

По умолчанию [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Параметры:**
| Параметр | Тип | Описание |
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
>  } while {
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
>  } while {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

По умолчанию [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |