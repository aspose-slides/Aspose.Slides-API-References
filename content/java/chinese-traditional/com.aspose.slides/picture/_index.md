---
title: Picture
second_title: Aspose.Slides for Java API 參考文件
description: 代表簡報中的一張圖片。
type: docs
url: /zh-hant/com.aspose.slides/picture/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

代表簡報中的一張圖片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | 返回或設定嵌入的影像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 返回或設定嵌入的影像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回或設定已連結影像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回或設定已連結影像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 返回影像變換效果的集合。 |
| [getPresentation()](#getPresentation--) | 返回簡報。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 與指定的物件比較。 |
| [hashCode()](#hashCode--) | 返回雜湊值。 |
| [getSlide()](#getSlide--) | 返回圖片的父投影片。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。 唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


版本。 唯讀 long。

**返回：**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


返回父 IPresentationComponent。 唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


返回或設定嵌入的影像。 可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


返回或設定嵌入的影像。 可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


返回或設定已連結影像的 URL。 可讀寫 String。

**返回：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


返回或設定已連結影像的 URL。 可讀寫 String。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


返回影像變換效果的集合。 唯讀 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**返回：**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回簡報。 唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


與指定的物件比較。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的物件。 |

**返回：**
boolean - 若物件相等則為 true，否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回雜湊值。

**返回：**
int - 雜湊值。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回圖片的父投影片。 唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)