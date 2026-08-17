---
title: IBlurEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: フィルも含むシェイプ全体に適用されるブラー効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/iblureffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

フィルも含むシェイプ全体に適用されるブラー効果を表す不変オブジェクトです。アルファを含むすべてのカラーチャンネルが影響を受けます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRadius()](#getRadius--) | ブラー半径を取得または設定します。 |
| [getGrow()](#getGrow--) | ブラー処理の結果としてオブジェクトの境界を拡張すべきかどうかを判断します。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ブラー半径を取得または設定します。 読み取り専用 double.

**戻り値:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

ブラー処理の結果としてオブジェクトの境界を拡張すべきかどうかを判断します。 True は境界が拡張されることを示し、false は拡張されないことを示します。 読み取り専用 boolean.

**戻り値:**
boolean