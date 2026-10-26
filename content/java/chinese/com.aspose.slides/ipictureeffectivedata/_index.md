---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /zh/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

不可变对象，包含有效的图片属性。

--------------------

此接口用作 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) 和 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) 的一部分。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | 返回嵌入的图像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回链接图像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 返回图像变换效果的集合。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


返回嵌入的图像。只读 [IPPImage](../../com.aspose.slides/ippimage)。

**返回:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


返回链接图像的 URL。只读 String。

**返回:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


返回图像变换效果的集合。只读 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)。

**返回:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)