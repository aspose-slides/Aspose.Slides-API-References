---
title: set_Character()
second_title: Aspose.Slides for C++ API 參考文件
description: "重音字符 此值應位於 (U+0300\\u2013U+036F) 或(U+20D0\\u2013U+20EF) 範圍內 預設值：結合抑揚重音 (U+0302)"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) 方法


重音字符 此值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 預設值：結合抑揚重音 (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## 備註


範例： 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 另見

* 類別 [IMathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)