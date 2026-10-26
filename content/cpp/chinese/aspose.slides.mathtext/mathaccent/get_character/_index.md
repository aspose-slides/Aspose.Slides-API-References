---
title: get_Character()
second_title: Aspose.Slides C++ API 参考
description: "重音字符 该值应在 (U+0300\\u2013U+036F) 或(U+20D0\\u2013U+20EF) 范围内 默认值：组合抑扬重音 (U+0302)"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() 方法


重音字符 该值应位于 (U+0300\\u2013U+036F) 或(U+20D0\\u2013U+20EF) 范围内 默认值：组合抑扬重音 (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## 备注


示例： 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 另请参见

* 类 [MathAccent](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)