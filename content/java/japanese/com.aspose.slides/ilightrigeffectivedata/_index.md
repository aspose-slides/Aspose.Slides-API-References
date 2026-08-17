---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /ja/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

有効なライトリグプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | ライトの方向。 |
| [getLightType()](#getLightType--) | シェイプに適用できるプリセットライト右を表します。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および軸回転を用いて回転が定義されます。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


ライトの方向です。 読み取り専用 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**戻り値:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


シェイプに適用できるプリセットライト右を表します。ライトリグは 3D シーンに対して特定の方向に配置されたライトのグループを表します。 読み取り専用 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**戻り値:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


緯度座標、経度座標、および軸回転を用いて回転が定義されます。戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転です。

**戻り値:**
float[] - Rotation coordinates as float[]