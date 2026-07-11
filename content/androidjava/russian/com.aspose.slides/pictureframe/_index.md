---
title: PictureFrame
second_title: Aspose.Slides для Android через Java API
description: Представляет кадр с изображением внутри.
type: docs
url: /ru/com.aspose.slides/pictureframe/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Представляет кадр с изображением внутри.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Добавляет аудиофрейм на слайд с указанными позицией и размером.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Добавляет изображение в ресурсы презентации.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Устанавливает изображение для аудиофрейма.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      // Сохраняет изменённую презентацию на диск
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Возвращает блокировки формы. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Возвращает объект PictureFillFormat для кадра изображения. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) кадра изображения. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) кадра изображения. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) кадра изображения. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) кадра изображения. |
| [isCameo()](#isCameo--) | Определяет, является ли объект PictureFrame типом Cameo. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Возвращает блокировки формы. Только для чтения [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Возвращаемое значение:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Возвращает или задает тип AutoShape для PictureFrame. Допустимы все элементы набора [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Возвращаемое значение:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Возвращает или задает тип AutoShape для PictureFrame. Допустимы все элементы набора [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Чтение/запись [ShapeType](../../com.aspose.slides/shapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Возвращает объект PictureFillFormat для кадра изображения. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращаемое значение:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Возвращает или задает масштаб высоты (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100%. Чтение/запись  float .

**Возвращаемое значение:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Возвращает или задает масштаб высоты (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100%. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Возвращает или задает масштаб ширины (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100%. Чтение/запись  float .

**Возвращаемое значение:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Возвращает или задает масштаб ширины (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100%. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Определяет, является ли объект PictureFrame типом Cameo. Только для чтения boolean.

**Возвращаемое значение:**
boolean