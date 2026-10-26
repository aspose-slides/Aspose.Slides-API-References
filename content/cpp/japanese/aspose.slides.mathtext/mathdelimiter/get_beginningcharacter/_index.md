---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "区切り開始文字は、開始、または開く区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() メソッド

区切り開始文字は、開始または開く区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
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