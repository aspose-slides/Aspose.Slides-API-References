---
title: IBlur
second_title: Aspose.Slides for Java API リファレンス
description: 塗りつぶしを含む図形全体に適用されるブラー効果を表します。
type: docs
url: /ja/com.aspose.slides/iblur/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

ブラー効果を表し、図形全体（塗りつぶしを含む）に適用されます。アルファを含むすべてのカラーチャンネルが影響を受けます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | ブラー半径を取得または設定します。 |
| [setRadius(double value)](#setRadius-double-) | ブラー半径を取得または設定します。 |
| [getGrow()](#getGrow--) | ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを決定します。 |
| [setGrow(boolean value)](#setGrow-boolean-) | ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを決定します。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ブラー半径を取得または設定します。読み取り/書き込み double。

**戻り値:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

ブラー半径を取得または設定します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを決定します。true は境界が拡張されることを示し、false は拡張されないことを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

ブラー処理の結果、オブジェクトの境界を拡張すべきかどうかを決定します。true は境界が拡張されることを示し、false は拡張されないことを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |