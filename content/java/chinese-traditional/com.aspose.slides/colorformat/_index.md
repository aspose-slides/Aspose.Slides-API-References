---
title: ColorFormat
second_title: Aspose.Slides for Java API 參考
description: 表示簡報中使用的顏色。
type: docs
url: /zh-hant/com.aspose.slides/colorformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面：**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

表示簡報中使用的顏色。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColorType()](#getColorType--) | 取得或設定顏色定義方法。 |
| [setColorType(int value)](#setColorType-int-) | 取得或設定顏色定義方法。 |
| [getColor()](#getColor--) | 取得結果顏色（已套用所有顏色轉換）。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 取得結果顏色（已套用所有顏色轉換）。 |
| [getPresetColor()](#getPresetColor--) | 取得或設定顏色預設值。 |
| [setPresetColor(int value)](#setPresetColor-int-) | 取得或設定顏色預設值。 |
| [getSystemColor()](#getSystemColor--) | 取得或設定由系統色彩表識別的顏色。 |
| [setSystemColor(int value)](#setSystemColor-int-) | 取得或設定由系統色彩表識別的顏色。 |
| [getSchemeColor()](#getSchemeColor--) | 取得或設定由色彩配置識別的顏色。 |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 取得或設定由色彩配置識別的顏色。 |
| [getR()](#getR--) | 取得或設定顏色的紅色成分。 |
| [setR(byte value)](#setR-byte-) | 取得或設定顏色的紅色成分。 |
| [getG()](#getG--) | 取得或設定顏色的綠色成分。 |
| [setG(byte value)](#setG-byte-) | 取得或設定顏色的綠色成分。 |
| [getB()](#getB--) | 取得或設定顏色的藍色成分。 |
| [setB(byte value)](#setB-byte-) | 取得或設定顏色的藍色成分。 |
| [getFloatR()](#getFloatR--) | 取得或設定顏色的紅色成分。 |
| [setFloatR(float value)](#setFloatR-float-) | 取得或設定顏色的紅色成分。 |
| [getFloatG()](#getFloatG--) | 取得或設定顏色的綠色成分。 |
| [setFloatG(float value)](#setFloatG-float-) | 取得或設定顏色的綠色成分。 |
| [getFloatB()](#getFloatB--) | 取得或設定顏色的藍色成分。 |
| [setFloatB(float value)](#setFloatB-float-) | 取得或設定顏色的藍色成分。 |
| [getHue()](#getHue--) | 取得或設定 HSL 表示法中顏色的色相成分。 |
| [setHue(float value)](#setHue-float-) | 取得或設定 HSL 表示法中顏色的色相成分。 |
| [getSaturation()](#getSaturation--) | 取得或設定 HSL 表示法中顏色的飽和度成分。 |
| [setSaturation(float value)](#setSaturation-float-) | 取得或設定 HSL 表示法中顏色的飽和度成分。 |
| [getLuminance()](#getLuminance--) | 取得或設定 HSL 表示法中顏色的亮度成分。 |
| [setLuminance(float value)](#setLuminance-float-) | 取得或設定 HSL 表示法中顏色的亮度成分。 |
| [getColorTransform()](#getColorTransform--) | 取得套用於顏色的顏色轉換集合。 |
| [toString(int format)](#toString-int-) | 取得表示目前顏色格式的字串。 |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | 從 "color" 複製顏色格式。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 檢查與指定物件是否相等。 |
| [hashCode()](#hashCode--) | 取得雜湊碼。 |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

取得或設定顏色定義方法。讀寫 [ColorType](../../com.aspose.slides/colortype)。

**回傳值：**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

取得或設定顏色定義方法。讀寫 [ColorType](../../com.aspose.slides/colortype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

取得結果顏色（已套用所有顏色轉換）。設定 RGB 顏色並清除所有顏色轉換。讀寫 java.awt.Color。

**回傳值：**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

取得結果顏色（已套用所有顏色轉換）。設定 RGB 顏色並清除所有顏色轉換。讀寫 java.awt.Color。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

取得或設定顏色預設值。讀寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**回傳值：**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

取得或設定顏色預設值。讀寫 [PresetColor](../../com.aspose.slides/presetcolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

取得或設定由系統色彩表識別的顏色。讀寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**回傳值：**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

取得或設定由系統色彩表識別的顏色。讀寫 [SystemColor](../../com.aspose.slides/systemcolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

取得或設定由色彩配置識別的顏色。讀寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**回傳值：**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

取得或設定由色彩配置識別的顏色。讀寫 [SchemeColor](../../com.aspose.slides/schemecolor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

取得或設定顏色的紅色成分。忽略所有顏色轉換。讀寫 byte 。

**回傳值：**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

取得或設定顏色的紅色成分。忽略所有顏色轉換。讀寫 byte 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

取得或設定顏色的綠色成分。忽略所有顏色轉換。

**回傳值：**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

取得或設定顏色的綠色成分。忽略所有顏色轉換。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

取得或設定顏色的藍色成分。忽略所有顏色轉換。讀寫 byte 。

**回傳值：**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

取得或設定顏色的藍色成分。忽略所有顏色轉換。讀寫 byte 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

取得或設定顏色的紅色成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

取得或設定顏色的紅色成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

取得或設定顏色的綠色成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

取得或設定顏色的綠色成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

取得或設定顏色的藍色成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

取得或設定顏色的藍色成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

取得或設定 HSL 表示法中顏色的色相成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

取得或設定 HSL 表示法中顏色的色相成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

取得或設定 HSL 表示法中顏色的飽和度成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

取得或設定 HSL 表示法中顏色的飽和度成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

取得或設定 HSL 表示法中顏色的亮度成分。忽略所有顏色轉換。讀寫 float 。

**回傳值：**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

取得或設定 HSL 表示法中顏色的亮度成分。忽略所有顏色轉換。讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

取得套用於顏色的顏色轉換集合。唯讀 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)。

**回傳值：**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

取得表示目前顏色格式的字串。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | int | 顏色字串格式的類型。 |

**回傳值：**
java.lang.String - 表示目前顏色格式的字串。

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

從 "color" 複製顏色格式。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

檢查與指定物件是否相等。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | Object. |

**回傳值：**
boolean - True if objects are equal, otherwise false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

取得雜湊碼。

**回傳值：**
int - Hash code.

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**回傳值：**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**回傳值：**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

取得父級 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**回傳值：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)