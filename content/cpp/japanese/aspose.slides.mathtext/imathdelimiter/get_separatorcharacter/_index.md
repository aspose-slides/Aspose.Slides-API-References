---
title: get_SeparatorCharacter()
second_title: C++ 用 Aspose.Slides API リファレンス
description: "区切り文字のセパレーター文字は、デリミタ オブジェクト内で引数を区切る文字を指定します。デフォルト: '|'."
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() メソッド

区切り文字のセパレーター文字は、デリミタ オブジェクト内で引数を区切る文字を指定します。デフォルト: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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