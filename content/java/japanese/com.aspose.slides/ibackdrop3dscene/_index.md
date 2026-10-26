---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java APIリファレンス
description: エフェクト（例えばグローや影）が、適用対象のシェイプに対してどのように適用されるかを定義する平面です。
type: docs
url: /ja/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

エフェクト（例えばグローや影）が、適用対象のシェイプに対してどのように適用されるかを定義する平面です。
## メソッド

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 法線ベクトルを取得または設定します。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 法線ベクトルを取得または設定します。 |
| [getAnchorPoint()](#getAnchorPoint--) | 3D空間内の点を取得または設定します。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D空間内の点を取得または設定します。 |
| [getUpVector()](#getUpVector--) | 上方向を表すベクトルを取得または設定します。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 上方向を表すベクトルを取得または設定します。 |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

法線ベクトルを取得または設定します。より正確に言うと、この属性はバックドロップ平面の面に対して垂直なベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

法線ベクトルを取得または設定します。より正確に言うと、この属性はバックドロップ平面の面に対して垂直なベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

3D空間内の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D 点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

3D空間内の点を取得または設定します。この点はバックドロップ平面を固定する空間上の点です。3D 点は X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

上方向を表すベクトルを取得または設定します。より正確に言うと、この属性はバックドロップ平面の面に対して上方向を示すベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**戻り値:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

上方向を表すベクトルを取得または設定します。より正確に言うと、この属性はバックドロップ平面の面に対して上方向を示すベクトルを定義します。ベクトルは X、Y、Z 座標を定義する 3 つの float 値の配列で表されます。読み取り/書き込み float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |