---
title: get_Character()
second_title: Aspose.Slides for C++ API 參考
description: "重音字符 此值應位於 (U+0300\\u2013U+036F) 或(U+20D0\\u2013U+20EF) 範圍內 預設值: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() 方法


Accent Character 此值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## 備註


範例： 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 參見

* 類別 [MathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)