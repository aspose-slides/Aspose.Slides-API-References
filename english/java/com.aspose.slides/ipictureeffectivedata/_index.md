---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
weight: 963
url: /java/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Immutable object which contains effective picture properties.

--------------------

This interface is used as a part of [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) and [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Returns the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Returns the embedded image. Read-only [IPPImage](../../com.aspose.slides/ippimage).

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returns linked image's URL. Read-only String.

**Returns:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Returns the collection of image transform effects. Read-only [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Returns:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
