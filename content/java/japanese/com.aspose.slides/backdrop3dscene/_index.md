---
title: Backdrop3DScene
second_title: Aspose.Slides for Java API リファレンス
description: エフェクト（光彩や影など）が、適用されるシェイプとの相対位置で適用される平面を定義します。
type: docs
url: /ja/com.aspose.slides/backdrop3dscene/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

シェイプに対して適用されるエフェクト（例えば、光彩や影）が、シェイプとの相対位置で適用される平面を定義します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 法線ベクトルを取得または設定します。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 法線ベクトルを取得または設定します。 |
| [getAnchorPoint()](#getAnchorPoint--) | 3D 空間内の点を取得または設定します。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D 空間内の点を取得または設定します。 |
| [getUpVector()](#getUpVector--) | 上方向ベクトルを取得または設定します。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 上方向ベクトルを取得または設定します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

法線ベクトルを取得または設定します。より正確には、この属性は背面平面の面に対して直交するベクトルを定義します。X、Y、Z 座標を定義する 3 つの float 値の配列で表されるベクトル。読み書き可能な float[]。

**戻り値:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

法線ベクトルを取得または設定します。より正確には、この属性は背面平面の面に対して直交するベクトルを定義します。X、Y、Z 座標を定義する 3 つの float 値の配列で表されるベクトル。読み書き可能な float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

3D 空間内の点を取得または設定します。この点は背面平面を固定する空間上の位置です。X、Y、Z 座標を定義する 3 つの float 値の配列で表される点。読み書き可能な float[]。

**戻り値:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

3D 空間内の点を取得または設定します。この点は背面平面を固定する空間上の位置です。X、Y、Z 座標を定義する 3 つの float 値の配列で表される点。読み書き可能な float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

上方向ベクトルを取得または設定します。より正確には、この属性は背面平面の面に対して上方向を表すベクトルを定義します。X、Y、Z 座標を定義する 3 つの float 値の配列で表されるベクトル。読み書き可能な float[]。

**戻り値:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

上方向ベクトルを取得または設定します。より正確には、この属性は背面平面の面に対して上方向を表すベクトルを定義します。X、Y、Z 座標を定義する 3 つの float 値の配列で表されるベクトル。読み書き可能な float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |