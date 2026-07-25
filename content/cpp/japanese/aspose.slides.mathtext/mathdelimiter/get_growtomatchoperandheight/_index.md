---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に拡大します。デフォルト値は true です。
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() method


BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に拡大します。デフォルト値は true です。

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## 備考


例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 参照

* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)