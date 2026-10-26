---
title: IThreeDFormatEffectiveData
second_title: Android 用 Aspose.Slides（Java API リファレンス）
description: 有効な3D書式設定プロパティを表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ithreedformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

有効な3-D書式設定プロパティを表す不変オブジェクトです。

--------------------

このインターフェイスは、[IThreeDFormat](../../com.aspose.slides/ithreedformat) インターフェイスと組み合わせて使用され、継承が適用された有効な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D輪郭の幅を返します。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 押し出し効果の高さを返します。 |
| [getDepth()](#getDepth--) | 3D形状の奥行きを返します。 |
| [getBevelTop()](#getBevelTop--) | 上部3Dベベルのタイプを返します。 |
| [getBevelBottom()](#getBevelBottom--) | 下部3Dベベルのタイプを返します。 |
| [getContourColor()](#getContourColor--) | 輪郭の色を返します。 |
| [getExtrusionColor()](#getExtrusionColor--) | 押し出しの色を返します。 |
| [getCamera()](#getCamera--) | カメラの設定を返します。 |
| [getLightRig()](#getLightRig--) | 光源のタイプを返します。 |
| [getMaterial()](#getMaterial--) | マテリアルのタイプを返します。 |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D輪郭の幅を返します。読み取り専用 double。

**戻り値:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

押し出し効果の高さを返します。読み取り専用 double。

**戻り値:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D形状の奥行きを返します。読み取り専用 double。

**戻り値:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

上部3Dベベルのタイプを返します。読み取り専用 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**戻り値:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

下部3Dベベルのタイプを返します。読み取り専用 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**戻り値:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

輪郭の色を返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

押し出しの色を返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

カメラの設定を返します。読み取り専用 [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)。

**戻り値:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

光源のタイプを返します。読み取り専用 [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)。

**戻り値:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

マテリアルのタイプを返します。読み取り専用 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**戻り値:**
int