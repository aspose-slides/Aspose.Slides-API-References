---
title: IDrawingGuide
second_title: Aspose.Slides Java API 參考
description: 表示可調整的繪圖輔助線。
type: docs
url: /zh-hant/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

表示可調整的繪圖輔助線。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 取得或設定繪圖輔助線的方向。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 取得或設定繪圖輔助線的方向。 |
| [getPosition()](#getPosition--) | 取得或設定繪圖輔助線相對於投影片左上角的點數位置。 |
| [setPosition(float value)](#setPosition-float-) | 取得或設定繪圖輔助線相對於投影片左上角的點數位置。 |
| [getColor()](#getColor--) | 取得或設定繪圖輔助線的顏色。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 取得或設定繪圖輔助線的顏色。 |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

取得或設定繪圖輔助線的方向。讀寫 [Orientation](../../com.aspose.slides/orientation)。

**傳回值:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

取得或設定繪圖輔助線的方向。讀寫 [Orientation](../../com.aspose.slides/orientation)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

取得或設定繪圖輔助線相對於投影片左上角的點數位置。讀寫 float.

--------------------

典型的數值範圍為水平輔助線從 0 到投影片高度，垂直輔助線則從 0 到投影片寬度。

**傳回值:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

取得或設定繪圖輔助線相對於投影片左上角的點數位置。讀寫 float.

--------------------

典型的數值範圍為水平輔助線從 0 到投影片高度，垂直輔助線則從 0 到投影片寬度。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

取得或設定繪圖輔助線的顏色。讀寫 java.awt.Color。

**傳回值:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

取得或設定繪圖輔助線的顏色。讀寫 java.awt.Color。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.Color |  |