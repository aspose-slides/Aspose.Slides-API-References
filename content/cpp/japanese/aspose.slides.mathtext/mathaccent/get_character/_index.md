---
title: get_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "アクセント文字 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() メソッド

アクセント文字 値は (U+0300\\u2013U+036F) または(U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## 備考

例: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 参照

* クラス [MathAccent](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)