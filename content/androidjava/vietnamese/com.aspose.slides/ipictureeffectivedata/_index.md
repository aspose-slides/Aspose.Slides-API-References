---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective picture properties.
type: docs
url: /vi/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

Đối tượng bất biến chứa các thuộc tính ảnh hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) và [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getImage()](#getImage--) | Trả về ảnh được nhúng. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về URL của ảnh được liên kết. |
| [getImageTransform()](#getImageTransform--) | Trả về tập hợp các hiệu ứng biến đổi ảnh. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Trả về ảnh được nhúng. Chỉ đọc [IPPImage](../../com.aspose.slides/ippimage).

**Trả về:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Trả về URL của ảnh được liên kết. Chỉ đọc String.

**Trả về:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```


Trả về tập hợp các hiệu ứng biến đổi ảnh. Chỉ đọc [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata).

**Trả về:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)