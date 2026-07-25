---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に拡大します。既定値は true です
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() メソッド

BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に拡大します。既定値は true です

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
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