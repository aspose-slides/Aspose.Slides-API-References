---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: 表示漸層格式。
type: docs
url: /zh-hant/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

表示漸層格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPosition()](#getPosition--) | 傳回或設定漸層停止點的位置 (0..1)。 |
| [setPosition(float value)](#setPosition-float-) | 傳回或設定漸層停止點的位置 (0..1)。 |
| [getColor()](#getColor--) | 傳回漸層停止點的顏色。 |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


傳回或設定漸層停止點的位置 (0..1)。可讀寫 float.

**返回:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


傳回或設定漸層停止點的位置 (0..1)。可讀寫 float.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


傳回漸層停止點的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)