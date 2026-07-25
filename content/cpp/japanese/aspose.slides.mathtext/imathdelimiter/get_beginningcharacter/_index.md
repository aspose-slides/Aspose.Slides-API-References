---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "区切り開始文字は、開始、または開く区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲む文字です。デフォルト値: '('."
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() メソッド

Delimiter Beginning Character は開始文字、すなわち開く区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲む文字です。デフォルト値: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## 備考

例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 参照

* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)