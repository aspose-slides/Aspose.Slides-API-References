---
title: get_Character()
second_title: Aspose.Slides for C++ API 參考
description: "重音字元 值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 的範圍內 預設值: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() 方法

重音字元 值應位於 (U+0300\\u2013U+036F) 或(U+20D0\\u2013U+20EF) 的範圍內 預設值: Combining Circumflex Accent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## 備註


範例: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 參見

* 類別 [IMathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)