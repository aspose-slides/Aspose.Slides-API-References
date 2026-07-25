---
title: get_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() メソッド

グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 下の括弧
```

## 参照

* クラス [IMathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)