---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, содержащий свойства заливки изображения.
type: docs
url: /ru/com.aspose.slides/ipicturefillformateffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий свойства заливки изображения.

--------------------

Этот интерфейс используется как часть [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getDpi()](#getDpi--) | Возвращает DPI, используемое для заливки изображения. |
| [getPictureFillMode()](#getPictureFillMode--) | Возвращает режим заливки изображения. |
| [getPicture()](#getPicture--) | Возвращает изображение. |
| [getCropLeft()](#getCropLeft--) | Возвращает количество процентов реальной ширины изображения, обрезанных слева. |
| [getCropTop()](#getCropTop--) | Возвращает количество процентов реальной высоты изображения, обрезанных сверху. |
| [getCropRight()](#getCropRight--) | Возвращает количество процентов реальной ширины изображения, обрезанных справа. |
| [getCropBottom()](#getCropBottom--) | Возвращает количество процентов реальной высоты изображения, обрезанных снизу. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Возвращает DPI, используемое для заливки изображения. Только для чтения int.

**Возвращает:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Возвращает режим заливки изображения. Только для чтения [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Возвращает:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Возвращает изображение. Только для чтения [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Возвращает:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Возвращает количество процентов реальной ширины изображения, обрезанных слева. Только для чтения float.

**Возвращает:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Возвращает количество процентов реальной высоты изображения, обрезанных сверху. Только для чтения float.

**Возвращает:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Возвращает количество процентов реальной ширины изображения, обрезанных справа. Только для чтения float.

**Возвращает:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Возвращает количество процентов реальной высоты изображения, обрезанных снизу. Только для чтения float.

**Возвращает:**
float