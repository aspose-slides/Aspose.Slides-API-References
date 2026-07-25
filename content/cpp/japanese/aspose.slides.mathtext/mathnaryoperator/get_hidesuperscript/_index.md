---
title: get_HideSuperscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 上付き文字を非表示
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathnaryoperator/get_hidesuperscript/
---
## MathNaryOperator::get_HideSuperscript() メソッド


上付き文字を非表示

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSuperscript() override
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 参照

* クラス [MathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)