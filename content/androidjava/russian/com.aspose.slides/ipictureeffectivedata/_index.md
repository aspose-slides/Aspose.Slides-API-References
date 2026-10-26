---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
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
| [getImage()](#getImage--) | Возвращает встроенное изображение. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает URL связанного изображения. |
| [getImageTransform()](#getImageTransform--) | Возвращает коллекцию эффектов преобразования изображения. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Возвращает встроенное изображение. Только для чтения [IPPImage](../../com.aspose.slides/ippimage).

**Возвращает:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Возвращает URL связанного изображения. Только для чтения String.

**Возвращает:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Возвращает коллекцию эффектов преобразования изображения. Только для чтения [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Возвращает:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)