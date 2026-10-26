---
title: IPictureFillFormatEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, содержащий свойства заливки изображения.
type: docs
url: /ru/com.aspose.slides/ipicturefillformateffectivedata/
---
**All Implemented Interfaces:**
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
| [getDpi()](#getDpi--) | Возвращает dpi, используемый для заполнения изображения. |
| [getPictureFillMode()](#getPictureFillMode--) | Возвращает режим заливки изображения. |
| [getPicture()](#getPicture--) | Возвращает изображение. |
| [getCropLeft()](#getCropLeft--) | Возвращает процент реальной ширины изображения, который обрезан слева от картинки. |
| [getCropTop()](#getCropTop--) | Возвращает процент реальной высоты изображения, который обрезан сверху картинки. |
| [getCropRight()](#getCropRight--) | Возвращает процент реальной ширины изображения, который обрезан справа от картинки. |
| [getCropBottom()](#getCropBottom--) | Возвращает процент реальной высоты изображения, который обрезан снизу картинки. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Возвращает dpi, используемый для заполнения изображения. Только для чтения int.

**Возвращаемое значение:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Возвращает режим заливки изображения. Только для чтения [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Возвращаемое значение:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Возвращает изображение. Только для чтения [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Возвращаемое значение:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Возвращает процент реальной ширины изображения, который обрезан слева от картинки. Только для чтения float.

**Возвращаемое значение:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Возвращает процент реальной высоты изображения, который обрезан сверху картинки. Только для чтения float.

**Возвращаемое значение:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Возвращает процент реальной ширины изображения, который обрезан справа от картинки. Только для чтения float.

**Возвращаемое значение:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Возвращает процент реальной высоты изображения, который обрезан снизу картинки. Только для чтения float.

**Возвращаемое значение:**
float