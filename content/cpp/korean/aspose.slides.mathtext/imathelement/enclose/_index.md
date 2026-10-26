---
title: Enclose()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 요소를 괄호로 감쌉니다
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() 메서드


수학 요소를 괄호로 감쌉니다

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### 반환 값

괄호를 포함하는 [IMathDelimiter](../../imathdelimiter/) 유형의 수학 요소
## 비고



예제: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) 메서드


이 요소를 괄호와 같은 지정 문자 또는 다른 문자로 프레임화합니다

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char16_t | 시작 문자 (보통 왼쪽 괄호) |
| endingCharacter | char16_t | 끝 문자 (보통 오른쪽 괄호) |

### 반환 값

지정된 문자를 프레임으로 포함하는 [IMathDelimiter](../../imathdelimiter/) 유형의 수학 요소
## 비고



예제: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathDelimiter](../../imathdelimiter/)
* 클래스 [IMathElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)