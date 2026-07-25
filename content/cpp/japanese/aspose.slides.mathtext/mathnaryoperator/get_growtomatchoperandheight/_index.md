---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: 演算子文字はオペランドの高さに合わせて縦方向に拡大します
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() メソッド


オペレーター文字は、オペランドの高さに合わせて縦方向に拡大します

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## 参照

* クラス [MathNaryOperator](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)