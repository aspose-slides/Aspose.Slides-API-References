---
title: IPictureFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет кадр с изображением внутри.
type: docs
url: /ru/com.aspose.slides/ipictureframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Представляет кадр с изображением внутри.
## Методы

| Метод | Описание |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Возвращает блокировки PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Возвращает объект PictureFillFormat для кадра с изображением. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Возвращает или задает масштаб высоты (относительно исходного размера изображения) кадра. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Возвращает или задает масштаб высоты (относительно исходного размера изображения) кадра. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Возвращает или задает масштаб ширины (относительно исходного размера изображения) кадра. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Возвращает или задает масштаб ширины (относительно исходного размера изображения) кадра. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Возвращает блокировки PictureFrame. Только для чтения [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Возвращаемое значение:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Возвращает объект PictureFillFormat для кадра с изображением. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращаемое значение:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Возвращает или задает масштаб высоты (относительно исходного размера изображения) кадра. Значение 1.0 соответствует 100%. Чтение/запись float.

**Возвращаемое значение:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Возвращает или задает масштаб высоты (относительно исходного размера изображения) кадра. Значение 1.0 соответствует 100%. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Возвращает или задает масштаб ширины (относительно исходного размера изображения) кадра. Значение 1.0 соответствует 100%. Чтение/запись float.

**Возвращаемое значение:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Возвращает или задает масштаб ширины (относительно исходного размера изображения) кадра. Значение 1.0 соответствует 100%. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |