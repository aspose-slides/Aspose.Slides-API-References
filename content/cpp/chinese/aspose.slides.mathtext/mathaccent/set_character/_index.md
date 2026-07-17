---
title: set_Character()
second_title: Aspose.Slides for C++ API 参考
description: "Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内。默认值：Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) 方法

Accent Character 值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内。默认值：Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## 备注

示例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 另请参阅

* 类 [MathAccent](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)