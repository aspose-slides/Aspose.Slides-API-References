---
title: get_Superscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 例えば積分の場合、上限を設定する上付き文字引数を指定します
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() メソッド


例えば積分の場合、上限を設定する上付き文字引数を指定します

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)