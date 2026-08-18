---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: デュートーン効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/iduotoneeffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

デュートーン効果を表す不変オブジェクトです。各ピクセルについて、線形補間を通じて clr1 と clr2 を組み合わせ、そのピクセルの新しい色を決定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor1()](#getColor1--) | 暗いピクセル用の目標カラー形式を返します。 |
| [getColor2()](#getColor2--) | 明るいピクセル用の目標カラー形式を返します。 |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

暗いピクセル用の目標カラー形式を返します。読み取り専用 java.awt.Color。

**返り値:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

明るいピクセル用の目標カラー形式を返します。読み取り専用 java.awt.Color。

**返り値:**
java.awt.Color