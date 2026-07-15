---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可變物件，包含有效的圖片屬性。
type: docs
url: /zh-hant/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

不可變物件，包含有效的圖片屬性。

--------------------

此介面作為 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) 和 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) 的一部分使用。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getImage()](#getImage--) | 傳回嵌入的圖像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 傳回已連結圖像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 傳回圖像轉換效果的集合。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

傳回嵌入的圖像。 唯讀 [IPPImage](../../com.aspose.slides/ippimage)。

**傳回:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

傳回已連結圖像的 URL。 唯讀 String。

**傳回:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

傳回圖像轉換效果的集合。 唯讀 [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)。

**傳回:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)