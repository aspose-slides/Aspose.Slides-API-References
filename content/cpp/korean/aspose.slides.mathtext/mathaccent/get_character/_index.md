---
title: get_Character()
second_title: Aspose.Slides for C++ API 참조
description: "Accent Character 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() 메서드

Accent Character 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## 비고

예시: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 참조

* 클래스 [MathAccent](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)