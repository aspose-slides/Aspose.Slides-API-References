---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，包含图片填充的属性。
type: docs
url: /zh/com.aspose.slides/ipicturefillformateffectivedata/
---
**所有实现的接口:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

不可变对象，包含图片填充的属性。

--------------------

此接口用作 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDpi()](#getDpi--) | 返回用于填充图片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回图片填充模式。 |
| [getPicture()](#getPicture--) | 返回图片。 |
| [getCropLeft()](#getCropLeft--) | 返回实际图像宽度的百分比，该百分比在图片左侧被裁剪。 |
| [getCropTop()](#getCropTop--) | 返回实际图像高度的百分比，该百分比在图片顶部被裁剪。 |
| [getCropRight()](#getCropRight--) | 返回实际图像宽度的百分比，该百分比在图片右侧被裁剪。 |
| [getCropBottom()](#getCropBottom--) | 返回实际图像高度的百分比，该百分比在图片底部被裁剪。 |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

返回用于填充图片的 dpi。只读 int。

**返回:**  
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

返回图片填充模式。只读 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**返回:**  
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

返回图片。只读 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**返回:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

返回实际图像宽度的百分比，该百分比在图片左侧被裁剪。只读 float。

**返回:**  
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

返回实际图像高度的百分比，该百分比在图片顶部被裁剪。只读 float。

**返回:**  
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

返回实际图像宽度的百分比，该百分比在图片右侧被裁剪。只读 float。

**返回:**  
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

返回实际图像高度的百分比，该百分比在图片底部被裁剪。只读 float。

**返回:**  
float