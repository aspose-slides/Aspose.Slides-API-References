---
title: set_HideSubscript()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 下付き文字を隠す
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathnaryoperator/set_hidesubscript/
---
## MathNaryOperator::set_HideSubscript(bool) メソッド


下付き文字を隠す

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSubscript(bool value) override
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