---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖表文字元素的格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

表示圖表文字元素的格式屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | 取得或設定 TextFrame 中的垂直錨點文字。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 取得或設定 TextFrame 中的垂直錨點文字。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True 為真，則文字應在框內水平置中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True 為真，則文字應在框內水平置中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 決定文字方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 決定文字方向。 |
| [getMarginLeft()](#getMarginLeft--) | 取得或設定 TextFrame 中的左側邊距（點）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 取得或設定 TextFrame 中的左側邊距（點）。 |
| [getMarginRight()](#getMarginRight--) | 取得或設定 TextFrame 中的右側邊距（點）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 取得或設定 TextFrame 中的右側邊距（點）。 |
| [getMarginTop()](#getMarginTop--) | 取得或設定 TextFrame 中的上側邊距（點）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 取得或設定 TextFrame 中的上側邊距（點）。 |
| [getMarginBottom()](#getMarginBottom--) | 取得或設定 TextFrame 中的下側邊距（點）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 取得或設定 TextFrame 中的下側邊距（點）。 |
| [getWrapText()](#getWrapText--) | 如果文字在 TextFrame 的邊距處換行則為 true。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文字在 TextFrame 的邊距處換行則為 true。 |
| [getAutofitType()](#getAutofitType--) | 取得或設定 文字的自動調整模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 取得或設定 文字的自動調整模式。 |
| [getRotationAngle()](#getRotationAngle--) | 指定套用於邊界框內文字的自訂旋轉。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定套用於邊界框內文字的自訂旋轉。 |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

取得或設定 TextFrame 中的垂直錨點文字。 讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**傳回:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

取得或設定 TextFrame 中的垂直錨點文字。 讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

如果 NullableBool.True 為真，則文字應在框內水平置中。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

如果 NullableBool.True 為真，則文字應在框內水平置中。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

決定文字方向。此屬性與 RotationAngle 屬性中的自訂角度共同彙總為最終的視覺文字旋轉值。 讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**傳回:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

決定文字方向。此屬性與 RotationAngle 屬性中的自訂角度共同彙總為最終的視覺文字旋轉值。 讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

取得或設定 TextFrame 中的左側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**傳回:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

取得或設定 TextFrame 中的左側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

取得或設定 TextFrame 中的右側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**傳回:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

取得或設定 TextFrame 中的右側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

取得或設定 TextFrame 中的上側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**傳回:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

取得或設定 TextFrame 中的上側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

取得或設定 TextFrame 中的下側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**傳回:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

取得或設定 TextFrame 中的下側邊距（點）。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

如果文字在 TextFrame 的邊距處換行則為 true。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2007/2013 中完整支援）。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

如果文字在 TextFrame 的邊距處換行則為 true。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2007/2013 中完整支援）。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

取得或設定 文字的自動調整模式。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**傳回:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

取得或設定 文字的自動調整模式。此屬性的變更僅對以下圖表部份產生特定影響：DataLabel 與 DataLabelFormat（在 PowerPoint 2013 中完整支援；PowerPoint 2007 中不影響呈現）。 讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉；若已指定，則獨立於圖形應用旋轉。即圖形可以有自己的旋轉，同時文字也可自行旋轉。最終的視覺文字旋轉值是此屬性與 TextVerticalType 屬性中預定義的垂直類型彙總得到的。 讀寫 float。

--------------------

> ```
> 請考慮一個形狀已套用順時針 90 度旋轉的情況。 
>  此外，文字本身亦套用逆時針 -90 度的旋轉 
>  逆時針套用於它。接著，產生的形狀會看起來
>  被旋轉，但其中的文字看起來彷彿根本沒有被旋轉。
> ```


**傳回:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉；若已指定，則獨立於圖形應用旋轉。即圖形可以有自己的旋轉，同時文字也可自行旋轉。最終的視覺文字旋轉值是此屬性與 TextVerticalType 屬性中預定義的垂直類型彙總得到的。 讀寫 float。

--------------------

> ```
> 請考慮一個形狀已套用順時針 90 度旋轉的情況。 
>  此外，文字本身也套用了 -90 度的逆時針旋轉 
>  逆時針套用於它。接著，產生的形狀會看起來
>  被旋轉，但其中的文字看起來彷彿根本沒有被旋轉。
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |