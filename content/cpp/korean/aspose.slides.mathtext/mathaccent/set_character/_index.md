---
title: set_Character()
second_title: Aspose.Slides for C++ API 참조
description: "억양 문자 값은 (U+0300\\u2013U+036F) 또는(U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합형 서캐비트 억양 (U+0302)"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) 메서드


억양 문자 값은 (U+0300\\u2013U+036F) 또는(U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합형 서캐비트 억양 (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## 비고


예시: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 참고

* 클래스 [MathAccent](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)