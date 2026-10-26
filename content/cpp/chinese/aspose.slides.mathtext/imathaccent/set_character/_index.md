---
title: set_Character()
second_title: Aspose.Slides C++ API 参考
description: "重音字符 该值应位于 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) 方法

重音字符 该值应位于 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 默认值：Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## 备注

示例：
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 参见

* 类 [IMathAccent](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)