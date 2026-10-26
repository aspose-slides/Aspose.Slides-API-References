---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 不可變物件，包含有效的光照裝置屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

不可變物件，包含有效的光照裝置屬性。

--------------------

此介面用作 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。

## Methods

| 方法 | 說明 |
| --- | --- |
| [getDirection()](#getDirection--) | 光線方向。 |
| [getLightType()](#getLightType--) | 表示可套用至形狀的預設光右側。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的，緯度和經度座標即如此。 |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光線方向。唯讀 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**Returns:**  
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

表示可套用至形狀的預設光右側。光源裝置表示相對於 3D 場景以特定方式定位的一組光源。唯讀 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**Returns:**  
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標以及繞軸的旋轉來定義的。返回陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。

**Returns:**  
float[] - 旋轉座標（float[]）