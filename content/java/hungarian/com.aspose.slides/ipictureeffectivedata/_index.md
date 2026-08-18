---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /hu/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Nem módosítható objektum, amely hatékony kép tulajdonságokat tartalmaz.

--------------------

Ez a felület a [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) és [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getImage()](#getImage--) | Visszaadja a beágyazott képet. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a hivatkozott kép URL-jét. |
| [getImageTransform()](#getImageTransform--) | Visszaadja a képek átalakítási hatásainak gyűjteményét. |
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

Visszaadja a hivatkozott kép URL-jét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

Visszaadja a képek átalakítási hatásainak gyűjteményét. Csak olvasható [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Visszatér:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)