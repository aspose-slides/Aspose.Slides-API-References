---
title: set_Character()
second_title: Aspose.Slides for C++ API Reference
description: "Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) method


Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Remarks


Example: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## See Also

* Class [IMathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)