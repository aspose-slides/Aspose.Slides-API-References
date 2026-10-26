---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /hu/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Módosíthatatlan objektum, amely a kép hatékony tulajdonságait tartalmazza.

--------------------

Ez az interfész a [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) és [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) részeként használatos.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getImage()](#getImage--) | Visszaadja a beágyazott képet. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a csatolt kép URL-címét. |
| [getImageTransform()](#getImageTransform--) | Visszaadja a képek transzformációs hatásainak gyűjteményét. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Visszaadja a beágyazott képet. Csak olvasható [IPPImage](../../com.aspose.slides/ippimage).

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Visszaadja a csatolt kép URL-címét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Visszaadja a képek transzformációs hatásainak gyűjteményét. Csak olvasható [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Visszatér:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)