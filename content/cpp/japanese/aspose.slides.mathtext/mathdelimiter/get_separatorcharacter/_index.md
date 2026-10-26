---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: "Delimiter Separator Character は、デリミタオブジェクト内で引数を区切る文字を指定します。デフォルト: '|'."
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() メソッド


Delimiter Separator Character は、デリミタオブジェクト内で引数を区切る文字を指定します。デフォルト: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## 備考


例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 参照

* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)