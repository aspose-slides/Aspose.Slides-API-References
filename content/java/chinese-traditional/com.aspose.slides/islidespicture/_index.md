---
title: ISlidesPicture
second_title: Aspose.Slides for Java API 參考
description: 代表簡報中的圖片。
type: docs
url: /zh-hant/com.aspose.slides/islidespicture/
---
**所有已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

表示簡報中的圖片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImage()](#getImage--) | 取得或設定嵌入的圖像。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 取得或設定嵌入的圖像。 |
| [getLinkPathLong()](#getLinkPathLong--) | 取得或設定連結圖像的 URL。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 取得或設定連結圖像的 URL。 |
| [getImageTransform()](#getImageTransform--) | 取得影像變換效果的集合。 |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

取得或設定嵌入的圖像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**回傳：**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

取得或設定嵌入的圖像。可讀寫 [IPPImage](../../com.aspose.slides/ippimage)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

取得或設定連結圖像的 URL。可讀寫 String。

**回傳：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

取得或設定連結圖像的 URL。可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

取得影像變換效果的集合。唯讀 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**回傳：**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)