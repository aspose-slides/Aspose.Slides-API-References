---
title: IGlow
second_title: Aspose.Slides の Java API リファレンス
description: オブジェクトのエッジの外側に、色がぼやけたアウトラインが追加される Glow 効果を表します。
type: docs
url: /ja/com.aspose.slides/iglow/
---
**実装されているすべてのインターフェイス：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Glow効果を表します。この効果では、オブジェクトのエッジの外側に色がぼやけたアウトラインが追加されます。
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

半径。 読み取り/書き込み可能な double。

**戻り値:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

半径。 読み取り/書き込み可能な double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

カラーフォーマット。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)