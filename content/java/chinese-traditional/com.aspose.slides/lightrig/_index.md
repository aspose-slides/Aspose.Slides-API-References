---
title: LightRig
second_title: Aspose.Slides for Java API 參考
description: 表示 LightRig。
type: docs
url: /zh-hant/com.aspose.slides/lightrig/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面：**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

表示 LightRig。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | 光的方向。 |
| [setDirection(int value)](#setDirection-int-) | 光的方向。 |
| [getLightType()](#getLightType--) | 表示可套用於形狀的預設光右。 |
| [setLightType(int value)](#setLightType-int-) | 表示可套用於形狀的預設光右。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的，緯度與經度座標即為此旋轉方式。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的，緯度與經度座標即為此旋轉方式。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回：**
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

光的方向。讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**傳回：**
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

光的方向。讀寫 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

表示可套用於形狀的預設光右。光源組表示一組相對於 3D 場景以特定方式定位的燈光。讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**傳回：**
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

表示可套用於形狀的預設光右。光源組表示一組相對於 3D 場景以特定方式定位的燈光。讀寫 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的。如果任一座標值為 Float.NaN，則所有旋轉皆未定義。

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

旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的。返回陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。如果未定義旋轉則返回 null。

**傳回：**
float[]