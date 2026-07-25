---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "デリミタ開始文字は、開始（または開く）デリミタ文字を指定します。数式デリミタは、括弧、角括弧、波括弧などの囲む文字です。デフォルトは '('です。"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) メソッド


デリミタ開始文字は、開始または開くデリミタ文字を指定します。数式デリミタは、括弧、角括弧、波括弧などの囲む文字です。デフォルトは '('です。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## 備考


例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 参照

* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)