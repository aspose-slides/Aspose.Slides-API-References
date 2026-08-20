---
title: IPictureEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 不可變的物件，包含有效的圖片屬性。
type: docs
url: /zh-hant/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

不可變的物件，包含有效的圖片屬性。

--------------------

此介面作為 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) 與 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) 的一部分使用。

## 方法

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | 返回嵌入的圖像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回已連結圖片的 URL。 |
| [getImageTransform()](#getImageTransform--) | 返回圖像變換效果的集合。 |

### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

返回嵌入的圖像。唯讀 [IPPImage](../../com.aspose.slides/ippimage)。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage)

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回已連結圖片的 URL。唯讀 String。

**返回：**
java.lang.String

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

返回圖像變換效果的集合。唯讀 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)。

**返回：**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)