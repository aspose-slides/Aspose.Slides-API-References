---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a gradient format.
type: docs
url: /zh-hant/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

表示漸層格式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPosition()](#getPosition--) | 返回或設定漸層停止點的位置 (0..1)。 |
| [setPosition(float value)](#setPosition-float-) | 返回或設定漸層停止點的位置 (0..1)。 |
| [getColor()](#getColor--) | 返回漸層停止點的顏色。 |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

返回或設定漸層停止點的位置 (0..1)。可讀寫 float.

**返回：**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

返回或設定漸層停止點的位置 (0..1)。可讀寫 float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

返回漸層停止點的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)