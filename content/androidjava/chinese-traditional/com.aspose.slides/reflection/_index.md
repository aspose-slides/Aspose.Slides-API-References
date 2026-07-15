---
title: Reflection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 Reflection 效果。
type: docs
url: /zh-hant/com.aspose.slides/reflection/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

代表 Reflection 效果。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值（百分比）在 alpha 漸層斜坡上的起始位置。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 指定起始 alpha 值（百分比）在 alpha 漸層斜坡上的起始位置。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定結束 alpha 值（百分比）在 alpha 漸層斜坡上的結束位置。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 指定結束 alpha 值（百分比）在 alpha 漸層斜坡上的結束位置。 |
| [getFadeDirection()](#getFadeDirection--) | 指定反射的偏移方向。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 指定反射的偏移方向。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 起始反射不透明度。 |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 起始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 結束反射不透明度。 |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 結束反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 反射的方向。 |
| [setDirection(float value)](#setDirection-float-) | 反射的方向。 |
| [getDistance()](#getDistance--) | 反射的距離。 |
| [setDistance(double value)](#setDistance-double-) | 反射的距離。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形對齊方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平斜角。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 指定水平斜角。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直斜角。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 指定垂直斜角。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定如果形狀旋轉，反射是否隨形狀旋轉。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指定如果形狀旋轉，反射是否隨形狀旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平縮放係數，負值縮放會導致翻轉。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 指定水平縮放係數，負值縮放會導致翻轉。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直縮放係數，負值縮放會導致翻轉。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 指定垂直縮放係數，負值縮放會導致翻轉。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Reflection 效果資料。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Reflection](../../com.aspose.slides/reflection) 是否等於目前的 [Reflection](../../com.aspose.slides/reflection)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

指定起始 alpha 值（百分比）在 alpha 漸層斜坡上的起始位置。讀寫 float。

**傳回值:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

指定起始 alpha 值（百分比）在 alpha 漸層斜坡上的起始位置。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

指定結束 alpha 值（百分比）在 alpha 漸層斜坡上的結束位置。讀寫 float。

**傳回值:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

指定結束 alpha 值（百分比）在 alpha 漸層斜坡上的結束位置。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

指定反射的偏移方向。（角度）讀寫 float。

**傳回值:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

指定反射的偏移方向。（角度）讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

起始反射不透明度。（百分比）讀寫 float。

**傳回值:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

起始反射不透明度。（百分比）讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

結束反射不透明度。（百分比）讀寫 float。

**傳回值:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

結束反射不透明度。（百分比）讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

模糊半徑。讀寫 double。

**傳回值:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

模糊半徑。讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

反射的方向。讀寫 float。

**傳回值:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

反射的方向。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

反射的距離。讀寫 double。

**傳回值:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

反射的距離。讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

矩形對齊方式。讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**傳回值:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

矩形對齊方式。讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

指定水平斜角。讀寫 double。

**傳回值:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

指定水平斜角。讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

指定垂直斜角。讀寫 double。

**傳回值:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

指定垂直斜角。讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

指定如果形狀旋轉，反射是否隨形狀旋轉。讀寫 boolean。

**傳回值:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

指定如果形狀旋轉，反射是否隨形狀旋轉。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

指定水平縮放係數，負值縮放會導致翻轉。（百分比）讀寫 double。

**傳回值:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

指定水平縮放係數，負值縮放會導致翻轉。（百分比）讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

指定垂直縮放係數，負值縮放會導致翻轉。（百分比）讀寫 double。

**傳回值:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

指定垂直縮放係數，負值縮放會導致翻轉。（百分比）讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

取得套用繼承後的有效 Reflection 效果資料。

**傳回值:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**傳回值:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

傳回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回值:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Reflection](../../com.aspose.slides/reflection) 是否等於目前的 [Reflection](../../com.aspose.slides/reflection)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [Reflection](../../com.aspose.slides/reflection)。 |

**傳回值:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回值:**
int - A hash code for the current object.