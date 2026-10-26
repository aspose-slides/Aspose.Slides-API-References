---
title: InnerShadow
second_title: Aspose.Slides for Android via Java API 參考
description: 代表內部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/innershadow/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

代表內部陰影效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 陰影方向。 |
| [setDirection(float value)](#setDirection-float-) | 陰影方向。 |
| [getDistance()](#getDistance--) | 陰影距離。 |
| [setDistance(double value)](#setDistance-double-) | 陰影距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影顏色。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Inner Shadow 效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [InnerShadow](../../com.aspose.slides/innershadow) 是否等於目前的 [InnerShadow](../../com.aspose.slides/innershadow)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半徑。可讀寫 double。

**回傳值：**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半徑。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

陰影方向。可讀寫 float。

**回傳值：**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

陰影方向。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

陰影距離。可讀寫 double。

**回傳值：**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

陰影距離。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

陰影顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**回傳值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

取得套用繼承後的有效 Inner Shadow 效果資料。

**回傳值：**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - A [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

回傳 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳值：**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**回傳值：**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

回傳父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**回傳值：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [InnerShadow](../../com.aspose.slides/innershadow) 是否等於目前的 [InnerShadow](../../com.aspose.slides/innershadow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [InnerShadow](../../com.aspose.slides/innershadow)。 |
**回傳值：**
boolean - 若物件相等則回傳 true；否則回傳 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**回傳值：**
int - 目前物件的雜湊碼。