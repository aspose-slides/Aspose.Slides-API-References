---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、区切り文字はオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です。
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) メソッド

BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、区切り文字はオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## 備考

例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 参照

* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)