---
title: IThreeDFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 3-D プロパティを表します。
type: docs
url: /ja/com.aspose.slides/ithreedformat/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3-D プロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D コンツアの幅を取得または設定します。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D コンツアの幅を取得または設定します。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 押し出し効果の高さを取得または設定します。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 押し出し効果の高さを取得または設定します。 |
| [getDepth()](#getDepth--) | 3D 形状の奥行きを取得または設定します。 |
| [setDepth(double value)](#setDepth-double-) | 3D 形状の奥行きを取得または設定します。 |
| [getBevelTop()](#getBevelTop--) | 上部 3D ベベルのタイプを取得または設定します。 |
| [getBevelBottom()](#getBevelBottom--) | 下部 3D ベベルのタイプを取得または設定します。 |
| [getContourColor()](#getContourColor--) | コンツアの色を取得または設定します。 |
| [getExtrusionColor()](#getExtrusionColor--) | 押し出しの色を取得または設定します。 |
| [getCamera()](#getCamera--) | カメラの設定を取得または設定します。 |
| [getLightRig()](#getLightRig--) | ライトのタイプを取得または設定します。 |
| [getMaterial()](#getMaterial--) | 素材のタイプを取得または設定します。 |
| [setMaterial(int value)](#setMaterial-int-) | 素材のタイプを取得または設定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な 3D 書式設定データを取得します。 |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D コンツアの幅を取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

3D コンツアの幅を取得または設定します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

押し出し効果の高さを取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

押し出し効果の高さを取得または設定します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D 形状の奥行きを取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

3D 形状の奥行きを取得または設定します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

上部 3D ベベルのタイプを取得します。読み取り専用 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**戻り値:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

下部 3D ベベルのタイプを取得します。読み取り専用 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**戻り値:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

コンツアの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

押し出しの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

カメラの設定を取得します。読み取り専用 [ICamera](../../com.aspose.slides/icamera)。

**戻り値:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

ライトのタイプを取得します。読み取り専用 [ILightRig](../../com.aspose.slides/ilightrig)。

**戻り値:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

素材のタイプを取得または設定します。読み取り/書き込み [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**戻り値:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

素材のタイプを取得または設定します。読み取り/書き込み [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

継承が適用された有効な 3D 書式設定データを取得します。

**戻り値:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).