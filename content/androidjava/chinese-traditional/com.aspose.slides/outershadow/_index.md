---
title: OuterShadow
second_title: Aspose.Slides for Android via Java API 參考
description: 表示外部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/outershadow/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

表示外部陰影效果。

## Methods

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑，以點為單位。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑，以點為單位。 |
| [getDirection()](#getDirection--) | 陰影方向，單位為度。 |
| [setDirection(float value)](#setDirection-float-) | 陰影方向，單位為度。 |
| [getDistance()](#getDistance--) | 陰影與物件的距離，以點為單位。 |
| [setDistance(double value)](#setDistance-double-) | 陰影與物件的距離，以點為單位。 |
| [getShadowColor()](#getShadowColor--) | 陰影的顏色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形對齊方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平斜切角度，單位為度。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平斜切角度，單位為度。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直斜切角度，單位為度。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直斜切角度，單位為度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指示陰影是否隨形狀一起旋轉。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指示陰影是否隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平縮放係數，以原始大小的百分比表示。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平縮放係數，以原始大小的百分比表示。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直縮放係數，以原始大小的百分比表示。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直縮放係數，以原始大小的百分比表示。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效外部陰影效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等於目前的 [OuterShadow](../../com.aspose.slides/outershadow)。 |
| [hashCode()](#hashCode--) | 為特定類型提供雜湊函式。 |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半徑，以點為單位。預設值 - 0 pt。可讀寫 double。

**Returns:**  
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半徑，以點為單位。預設值 - 0 pt。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

陰影方向，單位為度。預設值 - 0 � (從左到右)。可讀寫 float。

**Returns:**  
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

陰影方向，單位為度。預設值 - 0 � (從左到右)。可讀寫 float。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

陰影與物件的距離，以點為單位。預設值 - 0 pt。可讀寫 double。

**Returns:**  
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

陰影與物件的距離，以點為單位。預設值 - 0 pt。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

陰影的顏色。預設值 - 自動黑色（取決於主題）。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形對齊方式。預設值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**Returns:**  
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形對齊方式。預設值 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

水平斜切角度，單位為度。預設值 - 0 �。可讀寫 double。

**Returns:**  
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

水平斜切角度，單位為度。預設值 - 0 �。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

垂直斜切角度，單位為度。預設值 - 0 �。可讀寫 double。

**Returns:**  
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

垂直斜切角度，單位為度。預設值 - 0 �。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

指示陰影是否隨形狀一起旋轉。預設值 - true。可讀寫 boolean。

**Returns:**  
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

指示陰影是否隨形狀一起旋轉。預設值 - true。可讀寫 boolean。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

水平縮放係數，以原始大小的百分比表示。負值會導致翻轉。預設值 - 100%。可讀寫 double。

**Returns:**  
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

水平縮放係數，以原始大小的百分比表示。負值會導致翻轉。預設值 - 100%。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

垂直縮放係數，以原始大小的百分比表示。負值會導致翻轉。預設值 - 100%。可讀寫 double。

**Returns:**  
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

垂直縮放係數，以原始大小的百分比表示。負值會導致翻轉。預設值 - 100%。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```

取得套用繼承後的有效外部陰影效果資料。

**Returns:**  
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**Returns:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**Returns:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**Returns:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [OuterShadow](../../com.aspose.slides/outershadow) 是否等於目前的 [OuterShadow](../../com.aspose.slides/outershadow)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [OuterShadow](../../com.aspose.slides/outershadow)。 |

**Returns:**  
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

為特定類型提供雜湊函式。

**Returns:**  
int - A hash code for the current object.