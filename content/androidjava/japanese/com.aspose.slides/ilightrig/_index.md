---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /ja/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | 光の方向。 |
| [setDirection(int value)](#setDirection-int-) | 光の方向。 |
| [getLightType()](#getLightType--) | シェイプに適用できるプリセット light right を表します。 |
| [setLightType(int value)](#setLightType-int-) | シェイプに適用できるプリセット light right を表します。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および軸まわりの回転を緯度座標と経度座標として使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および軸まわりの回転を緯度座標と経度座標として使用して回転が定義されます。 |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光の方向。 読み取り/書き込み [LightingDirection](../../com.aspose.slides/lightingdirection)。

**戻り値:**
int

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

光の方向。 読み取り/書き込み [LightingDirection](../../com.aspose.slides/lightingdirection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

シェイプに適用できるプリセット light right を表します。 light rig は 3D シーンに対して特定の方向に配置された光のグループを表します。 読み取り/書き込み [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**戻り値:**
int

### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

シェイプに適用できるプリセット light right を表します。 light rig は 3D シーンに対して特定の方向に配置された光のグループを表します。 読み取り/書き込み [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、および軸まわりの回転を緯度座標と経度座標として使用して回転が定義されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| latitude | float | 緯度座標（float） |
| longitude | float | 経度座標（float） |
| revolution | float | 回転座標（float） |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および軸まわりの回転を緯度座標と経度座標として使用して回転が定義されます。戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転です。

**戻り値:**
float[] - 回転座標 (float[])