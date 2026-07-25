---
title: set_EndingCharacter()
second_title: Aspose.Slides の C++ API リファレンス
description: "Delimiter Ending Character は、終了または閉じる区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'."
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) メソッド


Delimiter Ending Character は、終了または閉じる区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'です。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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