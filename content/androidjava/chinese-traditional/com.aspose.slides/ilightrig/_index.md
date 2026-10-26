---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /zh-hant/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

表示 LightRig。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


光線方向。 讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**回傳值:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


光線方向。 讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


表示可以套用至形狀的預設光線方向。 Light rig 代表相對於 3D 場景特定方向排列的一組光源。 讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**回傳值:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


表示可以套用至形狀的預設光線方向。 Light rig 代表相對於 3D 場景特定方向排列的一組光源。 讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的，這些座標作為緯度和經度座標。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| latitude | float | Latitude coordinate float |
| longitude | float | Longitude coordinate float |
| revolution | float | Revolution coordinate float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的，這些座標作為緯度和經度座標。 回傳陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。

**回傳值:**
float[] - Rotation coordinates as float[]