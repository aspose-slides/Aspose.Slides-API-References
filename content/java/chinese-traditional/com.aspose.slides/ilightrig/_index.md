---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: 表示 LightRig。
type: docs
url: /zh-hant/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

表示 LightRig。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getDirection()](#getDirection--) | 光的方向。 |
| [setDirection(int value)](#setDirection-int-) | 光的方向。 |
| [getLightType()](#getLightType--) | 表示可套用於形狀的預設光右。 |
| [setLightType(int value)](#setLightType-int-) | 表示可套用於形狀的預設光右。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（以緯度和經度座標表示）來定義的。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（以緯度和經度座標表示）來定義的。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光的方向。可讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**返回值:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

光的方向。可讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

表示可套用於形狀的預設光右。光源組合表示相對於 3D 場景以特定方式定位的一組光。可讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**返回值:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

表示可套用於形狀的預設光右。光源組合表示相對於 3D 場景以特定方式定位的一組光。可讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（以緯度和經度座標表示）來定義的。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| latitude | float | 緯度座標 float |
| longitude | float | 經度座標 float |
| revolution | float | 旋轉座標 float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉（以緯度和經度座標表示）來定義的。返回陣列的第一個元素 - 緯度，第二個元素 - 經度，第三個元素 - 旋轉。

**返回值:**
float[] - 旋轉座標的 float[]