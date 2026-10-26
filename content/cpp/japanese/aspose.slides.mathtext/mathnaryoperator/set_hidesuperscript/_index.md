---
title: set_HideSuperscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 上付き文字を非表示にする
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/mathnaryoperator/set_hidesuperscript/
---
## MathNaryOperator::set_HideSuperscript(bool) メソッド

上付き文字を非表示にする

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSuperscript(bool value) override
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