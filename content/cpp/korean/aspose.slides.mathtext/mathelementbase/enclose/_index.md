---
title: Enclose()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 요소를 괄호로 둘러씁니다
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() 메서드


수학 요소를 괄호로 둘러씁니다

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### 반환 값

[IMathDelimiter](../../imathdelimiter/) 유형의 수학 요소이며 괄호를 포함합니다
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) 메서드


수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | 시작 문자(보통 왼쪽 대괄호) |
| endingCharacter | char16_t | 종료 문자(보통 오른쪽 대괄호) |

### 반환 값

[IMathDelimiter](../../imathdelimiter/) 유형의 수학 요소이며 지정된 문자를 프레임으로 포함합니다
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## 또한 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathDelimiter](../../imathdelimiter/)
* 클래스 [MathElementBase](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)