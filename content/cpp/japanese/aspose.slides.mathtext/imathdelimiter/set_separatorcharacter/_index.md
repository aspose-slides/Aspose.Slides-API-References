---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "Delimiter Separator Character は、デリミタ オブジェクト内の引数を区切る文字を指定します。デフォルトは '|'."
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) メソッド

Delimiter Separator Character は、デリミタ オブジェクト内の引数を区切る文字を指定します。デフォルトは '|' です。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## 備考


例:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 参照

* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)