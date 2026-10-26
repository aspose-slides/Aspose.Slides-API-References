---
title: set_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "グルーピング文字 デフォルト値: U+23DF (下カール括弧)"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) メソッド

グルーピング文字 デフォルト値: U+23DF (下カール括弧)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## 備考

例:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 下かっこ
```

## 参照

* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)