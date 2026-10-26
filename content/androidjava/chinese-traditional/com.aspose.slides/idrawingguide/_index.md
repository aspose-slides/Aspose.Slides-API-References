---
title: IDrawingGuide
second_title: Aspose.Slides for Android via Java API Reference
description: 表示一個可調整的繪圖參考線。
type: docs
url: /zh-hant/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

表示一個可調整的繪圖參考線。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrientation()](#getOrientation--) | 返回或設定繪圖參考線的方向。 |
| [setOrientation(byte value)](#setOrientation-byte-) | 返回或設定繪圖參考線的方向。 |
| [getPosition()](#getPosition--) | 返回或設定繪圖參考線的位置（以點為單位），相對於投影片左上角。 |
| [setPosition(float value)](#setPosition-float-) | 返回或設定繪圖參考線的位置（以點為單位），相對於投影片左上角。 |
| [getColor()](#getColor--) | 返回或設定繪圖參考線的顏色。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 返回或設定繪圖參考線的顏色。 |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


返回或設定繪圖參考線的方向。讀寫 [Orientation](../../com.aspose.slides/orientation)。

**返回：**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


返回或設定繪圖參考線的方向。讀寫 [Orientation](../../com.aspose.slides/orientation)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


返回或設定繪圖參考線的位置（以點為單位），相對於投影片左上角。讀寫 float。

--------------------

典型的值範圍為水平參考線從 0 到投影片高度，垂直參考線從 0 到投影片寬度。

**返回：**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


返回或設定繪圖參考線的位置（以點為單位），相對於投影片左上角。讀寫 float。

--------------------

典型的值範圍為水平參考線從 0 到投影片高度，垂直參考線從 0 到投影片寬度。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


返回或設定繪圖參考線的顏色。讀寫 java.lang.Integer。

**返回：**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


返回或設定繪圖參考線的顏色。讀寫 java.lang.Integer。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |