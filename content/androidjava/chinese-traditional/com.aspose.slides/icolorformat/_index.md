---
title: IColorFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示簡報中使用的顏色。
type: docs
url: /zh-hant/com.aspose.slides/icolorformat/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

表示簡報中使用的顏色。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorType()](#getColorType--) | 返回或設定顏色定義方法。 |
| [setColorType(int value)](#setColorType-int-) | 返回或設定顏色定義方法。 |
| [getColor()](#getColor--) | 返回結果顏色（套用所有顏色變換後）。 |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 返回結果顏色（套用所有顏色變換後）。 |
| [getPresetColor()](#getPresetColor--) | 返回或設定顏色預設值。 |
| [setPresetColor(int value)](#setPresetColor-int-) | 返回或設定顏色預設值。 |
| [getSystemColor()](#getSystemColor--) | 返回或設定由系統顏色表識別的顏色。 |
| [setSystemColor(int value)](#setSystemColor-int-) | 返回或設定由系統顏色表識別的顏色。 |
| [getSchemeColor()](#getSchemeColor--) | 返回或設定由顏色方案識別的顏色。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 返回或設定由顏色方案識別的顏色。 |
| [getR()](#getR--) | 返回或設定顏色的紅色分量。 |
| [setR(byte value)](#setR-byte-) | 返回或設定顏色的紅色分量。 |
| [getG()](#getG--) | 返回或設定顏色的綠色分量。 |
| [setG(byte value)](#setG-byte-) | 返回或設定顏色的綠色分量。 |
| [getB()](#getB--) | 返回或設定顏色的藍色分量。 |
| [setB(byte value)](#setB-byte-) | 返回或設定顏色的藍色分量。 |
| [getFloatR()](#getFloatR--) | 返回或設定顏色的紅色分量。 |
| [setFloatR(float value)](#setFloatR-float-) | 返回或設定顏色的紅色分量。 |
| [getFloatG()](#getFloatG--) | 返回或設定顏色的綠色分量。 |
| [setFloatG(float value)](#setFloatG-float-) | 返回或設定顏色的綠色分量。 |
| [getFloatB()](#getFloatB--) | 返回或設定顏色的藍色分量。 |
| [setFloatB(float value)](#setFloatB-float-) | 返回或設定顏色的藍色分量。 |
| [getHue()](#getHue--) | 返回或設定顏色的色相分量（HSL 表示）。 |
| [setHue(float value)](#setHue-float-) | 返回或設定顏色的色相分量（HSL 表示）。 |
| [getSaturation()](#getSaturation--) | 返回或設定顏色的飽和度分量（HSL 表示）。 |
| [setSaturation(float value)](#setSaturation-float-) | 返回或設定顏色的飽和度分量（HSL 表示）。 |
| [getLuminance()](#getLuminance--) | 返回或設定顏色的亮度分量（HSL 表示）。 |
| [setLuminance(float value)](#setLuminance-float-) | 返回或設定顏色的亮度分量（HSL 表示）。 |
| [getColorTransform()](#getColorTransform--) | 返回套用於顏色的顏色變換集合。 |
| [toString(int format)](#toString-int-) | 返回代表當前顏色格式的字串。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 從 "color" 複製顏色格式。 |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

返回或設定顏色定義方法。讀寫 [ColorType](../../com.aspose.slides/colortype)。

**返回：**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

返回或設定顏色定義方法。讀寫 [ColorType](../../com.aspose.slides/colortype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

返回結果顏色（套用所有顏色變換後）。設定 RGB 顏色並清除所有顏色變換。讀寫 java.lang.Integer。

**返回：**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

返回結果顏色（套用所有顏色變換後）。設定 RGB 顏色並清除所有顏色變換。讀寫 java.lang.Integer。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

返回或設定顏色預設值。讀寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**返回：**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

返回或設定顏色預設值。讀寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

返回或設定由系統顏色表識別的顏色。讀寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**返回：**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

返回或設定由系統顏色表識別的顏色。讀寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

返回或設定由顏色方案識別的顏色。讀寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**返回：**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

返回或設定由顏色方案識別的顏色。讀寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

返回或設定顏色的紅色分量。所有顏色變換均被忽略。讀寫 byte。

**返回：**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

返回或設定顏色的紅色分量。所有顏色變換均被忽略。讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

返回或設定顏色的綠色分量。所有顏色變換均被忽略。讀寫 byte。

**返回：**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

返回或設定顏色的綠色分量。所有顏色變換均被忽略。讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

返回或設定顏色的藍色分量。所有顏色變換均被忽略。讀寫 byte。

**返回：**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

返回或設定顏色的藍色分量。所有顏色變換均被忽略。讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

返回或設定顏色的紅色分量。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

返回或設定顏色的紅色分量。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

返回或設定顏色的綠色分量。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

返回或設定顏色的綠色分量。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

返回或設定顏色的藍色分量。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

返回或設定顏色的藍色分量。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

返回或設定顏色的色相分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

返回或設定顏色的色相分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

返回或設定顏色的飽和度分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

返回或設定顏色的飽和度分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

返回或設定顏色的亮度分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**返回：**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

返回或設定顏色的亮度分量（HSL 表示）。所有顏色變換均被忽略。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

返回套用於顏色的顏色變換集合。唯讀 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**返回：**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

返回代表當前顏色格式的字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | int | 顏色字串格式的類型。 |

**返回：**
java.lang.String - 代表當前顏色格式的字串。

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

從 "color" 複製顏色格式。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | 顏色 [IColorFormat](../../com.aspose.slides/icolorformat) |
