---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "区切り文字の終了文字は、終了または閉じる区切り文字を指定します。数学的な区切り文字は、括弧、角括弧、波括弧などの囲む文字です。デフォルトは ')'."
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() メソッド


区切り文字の終了文字は、終了または閉じる区切り文字を指定します。数学的な区切り文字は、括弧、角括弧、波括弧などの囲む文字です。デフォルトは ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## 備考


例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 参照

* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)