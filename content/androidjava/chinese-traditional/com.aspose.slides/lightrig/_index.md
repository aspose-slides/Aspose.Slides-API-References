---
title: LightRig
second_title: Aspose.Slides for Android Java API 參考
description: 表示 LightRig。
type: docs
url: /zh-hant/com.aspose.slides/lightrig/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面：**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

表示 LightRig.
## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | 光方向。 |
| [setDirection(int value)](#setDirection-int-) | 光方向。 |
| [getLightType()](#getLightType--) | 表示一個可套用於形狀的預設光線。 |
| [setLightType(int value)](#setLightType-int-) | 表示一個可套用於形狀的預設光線。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（作為緯度與經度座標）來定義的。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（作為緯度與經度座標）來定義的。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long.

**傳回值：**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

光方向。可讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**傳回值：**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

光方向。可讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

表示一個可套用於形狀的預設光線。光裝置表示相對於 3D 場景以特定方式定位的一組光源。可讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**傳回值：**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

表示一個可套用於形狀的預設光線。光裝置表示相對於 3D 場景以特定方式定位的一組光源。可讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（作為緯度與經度座標）來定義的。如果任何座標值為 Float.NaN，則所有旋轉未定義。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（作為緯度與經度座標）來定義的。返回陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。如果未定義旋轉，則返回 null。

**傳回值：**
float[]