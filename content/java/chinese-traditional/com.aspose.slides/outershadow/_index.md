---
title: OuterShadow
second_title: Aspose.Slides for Java API 參考
description: 表示外部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/outershadow/
---
**繼承:**
java.lang.Object

**全部已實作介面:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示外部陰影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑（單位：點）。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑（單位：點）。 |
| [getDirection()](#getDirection--) | 陰影方向（單位：度）。 |
| [setDirection(float value)](#setDirection-float-) | 陰影方向（單位：度）。 |
| [getDistance()](#getDistance--) | 陰影與物件之間的距離（單位：點）。 |
| [setDistance(double value)](#setDistance-double-) | 陰影與物件之間的距離（單位：點）。 |
| [getShadowColor()](#getShadowColor--) | 陰影顏色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形對齊方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平斜角（單位：度）。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平斜角（單位：度）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直斜角（單位：度）。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直斜角（單位：度）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指示陰影是否隨形狀一起旋轉。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指示陰影是否隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平縮放比例，以原始大小的百分比表示。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平縮放比例，以原始大小的百分比表示。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直縮放比例，以原始大小的百分比表示。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直縮放比例，以原始大小的百分比表示。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效外部陰影效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等於目前的 [OuterShadow](../../com.aspose.slides/outershadow)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半徑（單位：點）。預設值 - 0 pt。可讀寫 double。

**傳回：**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半徑（單位：點）。預設值 - 0 pt。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

陰影方向（單位：度）。預設值 - 0 �（從左至右）。可讀寫 float。

**傳回：**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

陰影方向（單位：度）。預設值 - 0 �（從左至右）。可讀寫 float。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

陰影與物件之間的距離（單位：點）。預設值 - 0 pt。可讀寫 double。

**傳回：**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

陰影與物件之間的距離（單位：點）。預設值 - 0 pt。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

陰影顏色。預設值 - 自動黑色（受佈景主題影響）。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形對齊方式。預設值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**傳回：**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形對齊方式。預設值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

水平斜角（單位：度）。預設值 - 0 �。可讀寫 double。

**傳回：**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

水平斜角（單位：度）。預設值 - 0 �。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

垂直斜角（單位：度）。預設值 - 0 �。可讀寫 double。

**傳回：**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

垂直斜角（單位：度）。預設值 - 0 �。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

指示陰影是否隨形狀一起旋轉。預設值 - true。可讀寫 boolean。

**傳回：**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

指示陰影是否隨形狀一起旋轉。預設值 - true。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

水平縮放比例，以原始大小的百分比表示。負值縮放會導致翻轉。預設值 - 100%。可讀寫 double。

**傳回：**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

水平縮放比例，以原始大小的百分比表示。負值縮放會導致翻轉。預設值 - 100%。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

垂直縮放比例，以原始大小的百分比表示。負值縮放會導致翻轉。預設值 - 100%。可讀寫 double。

**傳回：**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

垂直縮放比例，以原始大小的百分比表示。負值縮放會導致翻轉。預設值 - 100%。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

取得套用繼承後的有效外部陰影效果資料。

**傳回：**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**傳回：**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等於目前的 [OuterShadow](../../com.aspose.slides/outershadow)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [OuterShadow](../../com.aspose.slides/outershadow)。 |

**傳回：**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回：**
int - 目前物件的雜湊碼。