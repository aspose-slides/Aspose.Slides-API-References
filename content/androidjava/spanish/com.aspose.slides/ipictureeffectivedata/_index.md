---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene propiedades de imagen efectivas.
type: docs
url: /es/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Objeto inmutable que contiene propiedades de imagen efectivas.

--------------------

Esta interfaz se usa como parte de [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) y [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Métodos

| Method | Descripción |
| --- | --- |
| [getImage()](#getImage--) | Devuelve la imagen incrustada. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve la URL de la imagen vinculada. |
| [getImageTransform()](#getImageTransform--) | Devuelve la colección de efectos de transformación de imagen. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Devuelve la imagen incrustada. Solo lectura [IPPImage](../../com.aspose.slides/ippimage).

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Devuelve la URL de la imagen vinculada. Solo lectura String.

**Devuelve:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Devuelve la colección de efectos de transformación de imagen. Solo lectura [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Devuelve:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)