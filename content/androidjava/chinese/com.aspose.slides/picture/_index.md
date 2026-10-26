---
title: Picture
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿中的图片。
type: docs
url: /zh/com.aspose.slides/picture/
---
**继承：**
java.lang.Object

**所有实现的接口：**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

表示演示文稿中的图片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | 返回或设置嵌入的图像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 返回或设置嵌入的图像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或设置链接图像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或设置链接图像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 返回图像变换效果的集合。 |
| [getPresentation()](#getPresentation--) | 返回演示文稿。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 与指定对象比较。 |
| [hashCode()](#hashCode--) | 返回哈希值。 |
| [getSlide()](#getSlide--) | 返回图片的父幻灯片。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。只读 long。

**返回：**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

返回或设置嵌入的图像。可读写 [IPPImage](../../com.aspose.slides/ippimage)。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

返回或设置嵌入的图像。可读写 [IPPImage](../../com.aspose.slides/ippimage)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回或设置链接图像的 URL。可读写 String。

**返回：**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回或设置链接图像的 URL。可读写 String。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

返回图像变换效果的集合。只读 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**返回：**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

与指定对象比较。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的对象。 |

**返回：**
boolean - True if objects are equal, otherwise false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

返回哈希值。

**返回：**
int - 哈希值。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回图片的父幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)