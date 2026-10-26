---
title: set_Character()
second_title: Aspose.Slides for C++ API 참조
description: "그룹화 문자 기본값: U+23DF (하단 중괄호)"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) 메서드

그룹화 문자 기본값: U+23DF (하단 중괄호)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## 비고

예제: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 하단 괄호
```

## 참조

* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)