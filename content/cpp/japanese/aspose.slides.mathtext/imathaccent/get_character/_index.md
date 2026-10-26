---
title: get_Character()
second_title: Aspose.Slides for C++ API リファレンス
description: "アクセント文字 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() メソッド

アクセント文字 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## 備考

例: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 関連項目

* クラス [IMathAccent](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)