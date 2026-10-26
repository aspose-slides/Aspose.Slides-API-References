---
title: Delimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 구분 문자로 모든 하위 요소를 구분합니다 (괄호 없이)
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) 메서드

구분 기호 문자로 모든 하위 요소를 구분합니다 (괄호 없이)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char16_t | 구분 기호로 사용되는 문자 |

### 반환 값

[IMathDelimiter](../../imathdelimiter/) 요소의 인스턴스

## 비고

예:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)