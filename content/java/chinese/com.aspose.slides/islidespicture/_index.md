---
title: ISlidesPicture
second_title: Aspose.Slides for Java API 参考
description: 表示演示文稿中的图片。
type: docs
url: /zh/com.aspose.slides/islidespicture/
---
**已实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

表示演示文稿中的图片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | 返回或设置嵌入的图像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 返回或设置嵌入的图像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或设置链接图像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或设置链接图像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 返回图像变换效果的集合。 |
### getImage() {#getImage--}
``` 
public abstract IPPImage getImage()
```

返回或设置嵌入的图像。读/写 [IPPImage](../../com.aspose.slides/ippimage)。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

返回或设置嵌入的图像。读/写 [IPPImage](../../com.aspose.slides/ippimage)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回或设置链接图像的 URL。读/写 String。

**返回：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

返回或设置链接图像的 URL。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

返回图像变换效果的集合。只读 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**返回：**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)