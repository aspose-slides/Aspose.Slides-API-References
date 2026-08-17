---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /ja/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Represents LightRig.
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | ライトの方向。 |
| [setDirection(int value)](#setDirection-int-) | ライトの方向。 |
| [getLightType()](#getLightType--) | シェイプに適用できるプリセットライト右を表します。 |
| [setLightType(int value)](#setLightType-int-) | シェイプに適用できるプリセットライト右を表します。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および軸回りの回転を使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および軸回りの回転を使用して回転が定義されます。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

ライトの方向。 読み取り/書き込み [LightingDirection](../../com.aspose.slides/lightingdirection).

**戻り値:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

ライトの方向。 読み取り/書き込み [LightingDirection](../../com.aspose.slides/lightingdirection).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

シェイプに適用できるプリセットライト右を表します。Light rigは3Dシーンに対して特定の方向に配置されたライトのグループを表します。読み取り/書き込み [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**戻り値:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

シェイプに適用できるプリセットライト右を表します。Light rigは3Dシーンに対して特定の方向に配置されたライトのグループを表します。読み取り/書き込み [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、および軸回りの回転を使用して回転が定義されます。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | 緯度座標（float） |
| longitude | float | 経度座標（float） |
| revolution | float | 回転座標（float） |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および軸回りの回転を使用して回転が定義されます。返される配列の最初の要素は緯度、2番目は経度、3番目は回転です。

**戻り値:**
float[] - 回転座標（float[]）