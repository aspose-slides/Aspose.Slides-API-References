---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタは垂直方向に拡大し、オペランドの高さに合わせます。デフォルト値は true です。
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) メソッド


BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true のとき、デリミタは縦方向に拡大し、オペランドの高さに合わせます。デフォルト値は true です。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## 備考


例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 参照

* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)