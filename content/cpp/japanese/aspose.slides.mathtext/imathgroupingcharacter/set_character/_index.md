---
title: set_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "グループ化文字 デフォルト値: U+23DF (下カール括弧)"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) method


グループ化文字 デフォルト値: U+23DF (下カール括弧)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## 備考


例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 下の丸かっこ
```

## 関連項目

* クラス [IMathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)