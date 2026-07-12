---
title: IDuotoneEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: デュートーン効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/iduotoneeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

デュートーン効果を表す不変オブジェクトです。各ピクセルに対して、線形補間を介して clr1 と clr2 を組み合わせ、そのピクセルの新しい色を決定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor1()](#getColor1--) | 暗いピクセルの対象カラー形式を返します。 |
| [getColor2()](#getColor2--) | 明るいピクセルの対象カラー形式を返します。 |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

暗いピクセルの対象カラー形式を返します。 読み取り専用 java.lang.Integer.

**戻り値:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

明るいピクセルの対象カラー形式を返します。 読み取り専用 java.lang.Integer.

**戻り値:**
java.lang.Integer