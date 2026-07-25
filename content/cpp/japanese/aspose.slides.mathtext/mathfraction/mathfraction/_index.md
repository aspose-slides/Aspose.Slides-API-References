---
title: MathFraction()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された分子、分母、およびタイプで MathFraction を初期化します
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) コンストラクタ


指定された分子、分母、およびタイプで [MathFraction](../) を初期化します

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数タイプ |
## 備考



例: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) コンストラクタ


指定された分子と分母で、タイプ 'Bar' の [MathFraction](../) を初期化します

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
## 備考



例: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## 参照

* 列挙体 [MathFractionTypes](../../mathfractiontypes/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)