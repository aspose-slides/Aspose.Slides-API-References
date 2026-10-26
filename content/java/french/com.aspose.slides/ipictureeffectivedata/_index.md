---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objet immuable qui contient les propriétés effectives de l'image.
type: docs
url: /fr/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Objet immuable qui contient les propriétés effectives de l'image.

--------------------

Cette interface est utilisée dans le cadre de [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) et [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImage()](#getImage--) | Returns the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Renvoie l'image intégrée. Lecture seule [IPPImage](../../com.aspose.slides/ippimage).

**Renvoie:**  
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Renvoie l'URL de l'image liée. Lecture seule String.

**Renvoie:**  
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Renvoie la collection des effets de transformation d'image. Lecture seule [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Renvoie:**  
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)