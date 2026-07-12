---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 効果的なライトリグプロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

効果的なライトリグプロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) の一部として使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | 光の方向。 |
| [getLightType()](#getLightType--) | シェイプに適用できるプリセット光方向を表します。 |
| [getRotation()](#getRotation--) | 回転は、緯度座標、経度座標、および緯度と経度座標としての軸周りの回転を使用して定義されます。 |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光の方向です。読み取り専用 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**戻り値:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

シェイプに適用できるプリセット光方向を表します。ライトリグは、3Dシーンに対して特定の向きで配置された光のグループを表します。読み取り専用 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**戻り値:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

回転は、緯度座標、経度座標、および緯度と経度座標としての軸周りの回転を使用して定義されます。返却配列の最初の要素は緯度、2番目は経度、3番目は回転です。

**戻り値:**
float[] - 回転座標（float[]）