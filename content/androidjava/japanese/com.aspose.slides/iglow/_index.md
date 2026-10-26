---
title: IGlow
second_title: Aspose.Slides for Android の Java API リファレンス
description: オブジェクトのエッジの外側に、カラーのぼかしアウトラインが追加される Glow エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/iglow/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

オブジェクトのエッジの外側に、カラーのぼかしアウトラインが追加される Glow エフェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | 半径。 |
| [setRadius(double value)](#setRadius-double-) | 半径。 |
| [getColor()](#getColor--) | カラーフォーマット。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

半径。 読み取り/書き込み double.

**戻り値:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

半径。 読み取り/書き込み double.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

カラーフォーマット。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)