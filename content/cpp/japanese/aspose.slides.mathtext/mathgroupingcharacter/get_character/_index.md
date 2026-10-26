---
title: get_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "グルーピング文字 のデフォルト値: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() メソッド

グルーピング文字 のデフォルト値: U+23DF (BOTTOM CURLY BRACKET)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 下の丸かっこ
```

## 関連項目

* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)