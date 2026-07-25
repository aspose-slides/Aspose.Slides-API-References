---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "Delimiter Ending Character は、終了または閉じる区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'."
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() メソッド

Delimiter Ending Character は、終了または閉じる区切り文字を指定します。数学的区切り文字は、丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'です。

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## 備考

例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 参照

* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)