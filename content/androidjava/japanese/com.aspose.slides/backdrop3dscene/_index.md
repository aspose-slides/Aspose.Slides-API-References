---
title: Backdrop3DScene
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 光彩や影などのエフェクトが、適用される形状に対してどのように適用されるかを定義する平面です。
type: docs
url: /ja/com.aspose.slides/backdrop3dscene/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

影や光彩などのエフェクトが、適用される形状に対してどのように適用されるかを定義する平面です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 正規ベクトルを取得または設定します。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 正規ベクトルを取得または設定します。 |
| [getAnchorPoint()](#getAnchorPoint--) | 3 次元空間上の点を取得または設定します。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3 次元空間上の点を取得または設定します。 |
| [getUpVector()](#getUpVector--) | 上方向を表すベクトルを取得または設定します。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 上方向を表すベクトルを取得または設定します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

正規ベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して垂直なベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

正規ベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して垂直なベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

3 次元空間上の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D の点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

3 次元空間上の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D の点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

上方向を表すベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して上方向を表すベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

上方向を表すベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して上方向を表すベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |