---
title: ISlidesPicture
second_title: Aspose.Slides for Android via Java API 參考
description: 表示簡報中的圖片。
type: docs
url: /zh-hant/com.aspose.slides/islidespicture/
---
**已實作的所有介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

表示簡報中的圖片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getImage()](#getImage--) | 傳回或設定嵌入的圖像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 傳回或設定嵌入的圖像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 傳回或設定已連結圖像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 傳回或設定已連結圖像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 傳回圖像變換效果的集合。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

傳回或設定嵌入的圖像。讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**回傳：**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

傳回或設定嵌入的圖像。讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

傳回或設定已連結圖像的 URL。讀寫 String。

**回傳：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

傳回或設定已連結圖像的 URL。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

傳回圖像變換效果的集合。唯讀 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**回傳：**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)