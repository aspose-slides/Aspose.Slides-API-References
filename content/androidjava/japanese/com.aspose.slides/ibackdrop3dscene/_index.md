---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API リファレンス
description: エフェクト（例：グローやシャドウ）が適用される形状との関係で、効果が適用される平面を定義します。
type: docs
url: /ja/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

エフェクト（例：グローやシャドウ）が適用される形状との関係で、バックドロップ平面を定義します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 法線ベクトルを取得または設定します。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 法線ベクトルを取得または設定します。 |
| [getAnchorPoint()](#getAnchorPoint--) | 3D 空間内の点を取得または設定します。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D 空間内の点を取得または設定します。 |
| [getUpVector()](#getUpVector--) | 上向きベクトルを取得または設定します。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 上向きベクトルを取得または設定します。 |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


法線ベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して法線となるベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


法線ベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して法線となるベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


3D 空間内の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D 点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


3D 空間内の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D 点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


上向きベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して上向きとなるベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


上向きベクトルを取得または設定します。より正確には、この属性はバックドロップ平面の面に対して上向きとなるベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |