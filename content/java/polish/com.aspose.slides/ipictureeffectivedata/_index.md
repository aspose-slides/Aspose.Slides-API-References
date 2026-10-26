---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości obrazu.
type: docs
url: /pl/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości obrazu.

--------------------

Ten interfejs jest używany jako część [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) i [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getImage()](#getImage--) | Zwraca osadzony obraz. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca URL powiązanego obrazu. |
| [getImageTransform()](#getImageTransform--) | Zwraca kolekcję efektów transformacji obrazu. |
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


Zwraca URL powiązanego obrazu. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Zwraca kolekcję efektów transformacji obrazu. Tylko do odczytu [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Zwraca:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)