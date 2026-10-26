---
title: ISlidesPicture
second_title: Aspose.Slides Android 版（通过 Java API 参考）
description: 表示演示文稿中的图片。
type: docs
url: /zh/com.aspose.slides/islidespicture/
---
**所有已实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

表示演示文稿中的图片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | Returns or sets the embedded image. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returns or sets the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns of sets linked image's URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns of sets linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

返回或设置嵌入的图像。可读/可写 [IPPImage](../../com.aspose.slides/ippimage).

**返回:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

返回或设置嵌入的图像。可读/可写 [IPPImage](../../com.aspose.slides/ippimage).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回或设置链接图像的 URL。可读/可写 String.

**返回:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

返回或设置链接图像的 URL。可读/可写 String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

返回图像变换效果的集合。只读 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**返回:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)