---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 演算子文字はオペランドの高さに合わせて垂直方向に伸びます
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() メソッド


演算子文字は、そのオペランドの高さに合わせて垂直方向に伸びます

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
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