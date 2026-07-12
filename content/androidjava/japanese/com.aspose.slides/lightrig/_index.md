---
title: LightRig
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: LightRig を表します。
type: docs
url: /ja/com.aspose.slides/lightrig/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェース:**  
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)  
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | 光の方向。 |
| [setDirection(int value)](#setDirection-int-) | 光の方向。 |
| [getLightType()](#getLightType--) | シェイプに適用できるプリセット光源を表します。 |
| [setLightType(int value)](#setLightType-int-) | シェイプに適用できるプリセット光源を表します。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、そして軸回りの回転を使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、そして軸回りの回転を使用して回転が定義されます。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long。

**戻り値:**  
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

光の方向。読み書き可能 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**戻り値:**  
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

光の方向。読み書き可能 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

シェイプに適用できるプリセット光源を表します。ライトリグは 3D シーンに対して特定の方向で配置された光のグループを表します。読み書き可能 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**戻り値:**  
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

シェイプに適用できるプリセット光源を表します。ライトリグは 3D シーンに対して特定の方向で配置された光のグループを表します。読み書き可能 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、そして軸回りの回転を使用して回転が定義されます。いずれかの座標値が Float.NaN の場合、回転は未定義となります。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

緯度座標、経度座標、そして軸回りの回転を使用して回転が定義されます。戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転です。回転が定義されていない場合は null を返します。

**戻り値:**  
float[]