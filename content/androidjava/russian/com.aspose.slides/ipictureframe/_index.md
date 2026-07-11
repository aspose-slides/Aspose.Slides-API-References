---
title: IPictureFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет рамку с изображением внутри.
type: docs
url: /ru/com.aspose.slides/ipictureframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Представляет рамку с изображением внутри.
## Методы

| Метод | Описание |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Возвращает блокировки PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Возвращает объект PictureFillFormat для рамки с изображением. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки с изображением. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки с изображением. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки с изображением. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки с изображением. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Возвращает блокировки PictureFrame. Только для чтения [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Возвращает:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Возвращает объект PictureFillFormat для рамки с изображением. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки с изображением. Значение 1.0 соответствует 100 %. Чтение/запись float.

**Возвращает:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки с изображением. Значение 1.0 соответствует 100 %. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки с изображением. Значение 1.0 соответствует 100 %. Чтение/запись float.

**Возвращает:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки с изображением. Значение 1.0 соответствует 100 %. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |