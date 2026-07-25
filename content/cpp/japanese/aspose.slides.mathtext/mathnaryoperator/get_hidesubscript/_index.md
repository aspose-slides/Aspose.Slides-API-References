---
title: get_HideSubscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字の非表示
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() メソッド

下付き文字の非表示

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## 備考


例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 参照

* クラス [MathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)