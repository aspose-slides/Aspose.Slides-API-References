---
title: get_Character()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그룹화 문자 기본값: U+23DF (하단 중괄호)"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() 메서드


그룹화 문자 기본값: U+23DF (하단 중괄호)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## 비고


예시: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// 하단 괄호
```

## 참조

* 클래스 [MathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)