---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "Delimiter Beginning Character は、開始、または開く区切り文字を指定します。数式の区切り文字は、丸括弧、角括弧、波括弧などの囲む文字です。既定値: '('."
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) メソッド

Delimiter Beginning Character は、開始または開く区切り文字を指定します。数式区切り文字は、丸括弧、角括弧、波括弧などの囲む文字です。既定値: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
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