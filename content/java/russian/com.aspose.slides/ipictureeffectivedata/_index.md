---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства изображения.
type: docs
url: /ru/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства изображения.

--------------------

Этот интерфейс используется как часть [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) и [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getImage()](#getImage--) | Возвращает внедренное изображение. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает URL связанного изображения. |
| [getImageTransform()](#getImageTransform--) | Возвращает коллекцию эффектов трансформации изображения. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Возвращает внедренное изображение. Только для чтения [IPPImage](../../com.aspose.slides/ippimage).

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Возвращает URL связанного изображения. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Возвращает коллекцию эффектов трансформации изображения. Только для чтения [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Возвращаемое значение:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)