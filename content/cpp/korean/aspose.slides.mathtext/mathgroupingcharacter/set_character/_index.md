---
title: set_Character()
second_title: Aspose.Slides for C++ API 참조
description: "그룹화 문자 기본값: U+23DF (하단 중괄호)"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) 메서드

그룹화 문자 기본값: U+23DF (하단 중괄호)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## 비고

예:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 하단 괄호
```

## 참고

* 클래스 [MathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)