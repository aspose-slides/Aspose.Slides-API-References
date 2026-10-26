---
title: IBlurEffectiveData
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: 形状全体とその塗りつぶしに適用されるブラー効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/iblureffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

形状全体とその塗りつぶしに適用されるブラー効果を表す不変オブジェクトです。アルファを含むすべてのカラーチャンネルが影響を受けます。

## メソッド

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | ブラー半径を取得または設定します。 |
| [getGrow()](#getGrow--) | ブラー処理の結果としてオブジェクトの境界を拡張すべきかどうかを決定します。 |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ブラー半径を取得または設定します。読み取り専用の double。

**Returns:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

ブラー処理の結果としてオブジェクトの境界を拡張すべきかどうかを決定します。True は境界が拡大されることを示し、false は拡大されないことを示します。読み取り専用の boolean。

**Returns:**
boolean