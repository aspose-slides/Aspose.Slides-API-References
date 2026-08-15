---
title: set_Character()
second_title: Aspose.Slides for C++ API 參考文件
description: "Accent Character 的值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內。預設值：Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) 方法


Accent Character 的值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內。預設值：Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## 備註


範例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 另請參閱

* 類別 [MathAccent](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)