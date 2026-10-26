---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可變物件，包含有效的光源裝置屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilightrigeffectivedata/
---
```
public interface ILightRigEffectiveData
```

不可變物件，包含有效的光源裝置屬性。

--------------------

此介面用於 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 光線方向。 |
| [getLightType()](#getLightType--) | 表示可套用於形狀的預設右側光。 |
| [getRotation()](#getRotation--) | 透過緯度座標、經度座標以及繞軸的旋轉來定義旋轉。 |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光線方向。 唯讀 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**傳回值:**  
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

表示可套用於形狀的預設右側光。光源裝置代表相對於 3D 場景以特定方式定位的一組光線。 唯讀 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**傳回值:**  
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

透過緯度座標、經度座標以及繞軸的旋轉來定義旋轉。返回陣列的第一個元素為緯度，第二個為經度，第三個為繞軸旋轉。

**傳回值:**  
float[] - 旋轉座標（float[]）