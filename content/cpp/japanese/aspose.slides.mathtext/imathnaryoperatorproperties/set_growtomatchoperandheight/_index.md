---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: 演算子文字はオペランドの高さに合わせて垂直方向に伸びます
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) メソッド

演算子文字はオペランドの高さに合わせて垂直方向に伸びます

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## 備考

例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 参照

* クラス [IMathNaryOperatorProperties](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)