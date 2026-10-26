---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "デリミタの終了文字は、終了または閉じるデリミタ文字を指定します。数学的デリミタは、丸括弧、角括弧、波括弧などの囲む文字です。デフォルトは ')'."
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) メソッド


デリミタの終了文字は、終了または閉じるデリミタ文字を指定します。数学的デリミタは、丸括弧、角括弧、波括弧などの囲む文字です。デフォルト: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## 備考


例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 参照

* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)