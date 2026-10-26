---
title: IColorFormat
second_title: Aspose.Slides for Java API 參考文件
description: 表示在簡報中使用的顏色。
type: docs
url: /zh-hant/com.aspose.slides/icolorformat/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

表示在簡報中使用的顏色。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorType()](#getColorType--) | 回傳或設定顏色定義方法。 |
| [setColorType(int value)](#setColorType-int-) | 回傳或設定顏色定義方法。 |
| [getColor()](#getColor--) | 回傳結果顏色（已套用所有顏色轉換）。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 回傳結果顏色（已套用所有顏色轉換）。 |
| [getPresetColor()](#getPresetColor--) | 回傳或設定顏色預設值。 |
| [setPresetColor(int value)](#setPresetColor-int-) | 回傳或設定顏色預設值。 |
| [getSystemColor()](#getSystemColor--) | 回傳或設定系統色表中辨識的顏色。 |
| [setSystemColor(int value)](#setSystemColor-int-) | 回傳或設定系統色表中辨識的顏色。 |
| [getSchemeColor()](#getSchemeColor--) | 回傳或設定色彩配置方案中辨識的顏色。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 回傳或設定色彩配置方案中辨識的顏色。 |
| [getR()](#getR--) | 回傳或設定顏色的紅色成分。 |
| [setR(byte value)](#setR-byte-) | 回傳或設定顏色的紅色成分。 |
| [getG()](#getG--) | 回傳或設定顏色的綠色成分。 |
| [setG(byte value)](#setG-byte-) | 回傳或設定顏色的綠色成分。 |
| [getB()](#getB--) | 回傳或設定顏色的藍色成分。 |
| [setB(byte value)](#setB-byte-) | 回傳或設定顏色的藍色成分。 |
| [getFloatR()](#getFloatR--) | 回傳或設定顏色的紅色成分。 |
| [setFloatR(float value)](#setFloatR-float-) | 回傳或設定顏色的紅色成分。 |
| [getFloatG()](#getFloatG--) | 回傳或設定顏色的綠色成分。 |
| [setFloatG(float value)](#setFloatG-float-) | 回傳或設定顏色的綠色成分。 |
| [getFloatB()](#getFloatB--) | 回傳或設定顏色的藍色成分。 |
| [setFloatB(float value)](#setFloatB-float-) | 回傳或設定顏色的藍色成分。 |
| [getHue()](#getHue--) | 回傳或設定顏色在 HSL 表示法中的色相成分。 |
| [setHue(float value)](#setHue-float-) | 回傳或設定顏色在 HSL 表示法中的色相成分。 |
| [getSaturation()](#getSaturation--) | 回傳或設定顏色在 HSL 表示法中的飽和度成分。 |
| [setSaturation(float value)](#setSaturation-float-) | 回傳或設定顏色在 HSL 表示法中的飽和度成分。 |
| [getLuminance()](#getLuminance--) | 回傳或設定顏色在 HSL 表示法中的亮度成分。 |
| [setLuminance(float value)](#setLuminance-float-) | 回傳或設定顏色在 HSL 表示法中的亮度成分。 |
| [getColorTransform()](#getColorTransform--) | 回傳套用於顏色的顏色轉換集合。 |
| [toString(int format)](#toString-int-) | 回傳表示目前顏色格式的字串。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 從 "color" 複製顏色格式。 |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

回傳或設定顏色定義方法。讀/寫 [ColorType](../../com.aspose.slides/colortype)。

**回傳:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

回傳或設定顏色定義方法。讀/寫 [ColorType](../../com.aspose.slides/colortype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

回傳結果顏色（已套用所有顏色轉換）。設定 RGB 顏色並清除所有顏色轉換。讀/寫 java.awt.Color。

**回傳:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

回傳結果顏色（已套用所有顏色轉換）。設定 RGB 顏色並清除所有顏色轉換。讀/寫 java.awt.Color。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

回傳或設定顏色預設值。讀/寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**回傳:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

回傳或設定顏色預設值。讀/寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

回傳或設定系統色表中辨識的顏色。讀/寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**回傳:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

回傳或設定系統色表中辨識的顏色。讀/寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

回傳或設定色彩配置方案中辨識的顏色。讀/寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**回傳:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

回傳或設定色彩配置方案中辨識的顏色。讀/寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

回傳或設定顏色的紅色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**回傳:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

回傳或設定顏色的紅色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

回傳或設定顏色的綠色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**回傳:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

回傳或設定顏色的綠色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

回傳或設定顏色的藍色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**回傳:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

回傳或設定顏色的藍色成分。所有顏色轉換皆被忽略。讀/寫 byte。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

回傳或設定顏色的紅色成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

回傳或設定顏色的紅色成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

回傳或設定顏色的綠色成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

回傳或設定顏色的綠色成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

回傳或設定顏色的藍色成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

回傳或設定顏色的藍色成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

回傳或設定顏色在 HSL 表示法中的色相成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

回傳或設定顏色在 HSL 表示法中的色相成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

回傳或設定顏色在 HSL 表示法中的飽和度成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

回傳或設定顏色在 HSL 表示法中的飽和度成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

回傳或設定顏色在 HSL 表示法中的亮度成分。所有顏色轉換皆被忽略。讀/寫 float。

**回傳:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

回傳或設定顏色在 HSL 表示法中的亮度成分。所有顏色轉換皆被忽略。讀/寫 float。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

回傳套用於顏色的顏色轉換集合。唯讀 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**回傳:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

回傳表示目前顏色格式的字串。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| format | int | 顏色字串格式的類型。 |

**回傳:**
java.lang.String - 表示目前顏色格式的字串。

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

從 "color" 複製顏色格式。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |