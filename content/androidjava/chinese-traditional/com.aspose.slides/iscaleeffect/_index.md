---
title: IScaleEffect
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示動畫縮放效果。
type: docs
url: /zh-hant/com.aspose.slides/iscaleeffect/
---
**所有已實作介面：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

表示動畫縮放效果。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | 判斷內容是否應該放大。 |
| [setZoomContent(byte value)](#setZoomContent-byte-) | 判斷內容是否應該放大。 |
| [getFrom()](#getFrom--) | 指定動畫起始的 x/y 座標（以百分比表示）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定動畫起始的 x/y 座標（以百分比表示）。 |
| [getTo()](#getTo--) | 指定動畫縮放效果的目標位置（以百分比表示）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定動畫縮放效果的目標位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述動畫的相對偏移量（以百分比表示）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述動畫的相對偏移量（以百分比表示）。 |

### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

判斷內容是否應該放大。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**回傳：**
byte

### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

判斷內容是否應該放大。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

指定動畫起始的 x/y 座標（以百分比表示）。可讀寫 android.graphics.PointF。

**回傳：**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

指定動畫起始的 x/y 座標（以百分比表示）。可讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

指定動畫縮放效果的目標位置（以百分比表示）。可讀寫 android.graphics.PointF。

**回傳：**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

指定動畫縮放效果的目標位置（以百分比表示）。可讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

描述動畫的相對偏移量（以百分比表示）。可讀寫 android.graphics.PointF。

**回傳：**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

描述動畫的相對偏移量（以百分比表示）。可讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |