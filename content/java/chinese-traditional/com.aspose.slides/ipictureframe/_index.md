---
title: IPictureFrame
second_title: Aspose.Slides for Java API 參考文件
description: 表示內含圖片的框架。
type: docs
url: /zh-hant/com.aspose.slides/ipictureframe/
---
**所有已實作的介面:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

表示內含圖片的框架。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 傳回 PictureFrame 的鎖定。 |
| [getPictureFormat()](#getPictureFormat--) | 傳回圖片框的 PictureFillFormat 物件。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 傳回或設定圖片框的高度比例（相對於原始圖片大小）。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 傳回或設定圖片框的高度比例（相對於原始圖片大小）。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 傳回或設定圖片框的寬度比例（相對於原始圖片大小）。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 傳回或設定圖片框的寬度比例（相對於原始圖片大小）。 |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

傳回 PictureFrame 的鎖定。唯讀 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**傳回：**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

傳回圖片框的 PictureFillFormat 物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**傳回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

傳回或設定圖片框的高度比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 float。

**傳回：**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

傳回或設定圖片框的高度比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

傳回或設定圖片框的寬度比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 float。

**傳回：**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

傳回或設定圖片框的寬度比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |