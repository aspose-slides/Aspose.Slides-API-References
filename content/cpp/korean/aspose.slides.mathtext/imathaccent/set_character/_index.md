---
title: set_Character()
second_title: Aspose.Slides C++ API 레퍼런스
description: "악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 결합 서캐플 악센트 (U+0302)"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) 메서드


악센트 문자 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. 기본값: 조합 서캐플 악센트 (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## 비고


예시: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## 참조

* 클래스 [IMathAccent](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)