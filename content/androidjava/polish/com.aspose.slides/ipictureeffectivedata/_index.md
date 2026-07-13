---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /pl/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości obrazu.

--------------------

Ten interfejs jest używany jako część [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) i [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Metody

| Method | Opis |
| --- | --- |
| [getImage()](#getImage--) | Zwraca osadzony obraz. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca adres URL powiązanego obrazu. |
| [getImageTransform()](#getImageTransform--) | Zwraca kolekcję efektów przekształcenia obrazu. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Zwraca osadzony obraz. Tylko do odczytu [IPPImage](../../com.aspose.slides/ippimage).

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Zwraca adres URL powiązanego obrazu. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Zwraca kolekcję efektów przekształcenia obrazu. Tylko do odczytu [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Zwraca:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)