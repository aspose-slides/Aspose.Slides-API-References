---
title: Picture
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 代表簡報中的圖片。
type: docs
url: /zh-hant/com.aspose.slides/picture/
---
**繼承:**  
java.lang.Object  

**所有已實作的介面:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)  
```
public final class Picture implements IPVIObject, ISlidesPicture
```

代表簡報中的圖片。  

## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | 傳回或設定內嵌影像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 傳回或設定內嵌影像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 傳回或設定連結影像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 傳回或設定連結影像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 傳回影像變換效果的集合。 |
| [getPresentation()](#getPresentation--) | 傳回簡報。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 與指定的物件比較。 |
| [hashCode()](#hashCode--) | 傳回雜湊值。 |
| [getSlide()](#getSlide--) | 傳回圖片的父投影片。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**  
com.aspose.slides.IDOMObject  

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**傳回:**  
long  

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

傳回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)  

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

傳回或設定內嵌影像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**傳回:**  
[IPPImage](../../com.aspose.slides/ippimage)  

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

傳回或設定內嵌影像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

傳回或設定連結影像的 URL。可讀寫 String。

**傳回:**  
java.lang.String  

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

傳回或設定連結影像的 URL。可讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

傳回影像變換效果的集合。唯讀 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**傳回:**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)  

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回:**  
[IPresentation](../../com.aspose.slides/ipresentation)  

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

與指定的物件比較。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的物件。 |

**傳回:**  
boolean - 若物件相等則為 True，否則為 false。  

### hashCode() {#hashCode--}
```
public int hashCode()
```

傳回雜湊值。

**傳回:**  
int - 雜湊值。  

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回圖片的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)  