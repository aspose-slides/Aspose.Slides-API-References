---
title: Enclose()
second_title: Aspose.Slides for C++ API 참조
description: 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레이밍합니다.
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) 메서드


수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레이밍합니다.

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char16_t | 시작 문자(보통 왼쪽 괄호) |
| endingCharacter | char16_t | 끝 문자(보통 오른쪽 괄호) |

### 반환 값

*beginningCharacter* 및 *endingCharacter* 가 null이면 해당 속성에만 값이 할당되고 새 객체가 생성되지 않습니다(이 인스턴스를 반환함). 그렇지 않으면 지정된 문자를 프레이밍으로 포함하고 이 [MathDelimiter](../) 인스턴스를 프레임 안에 넣은 Delimiter 유형의 새 수학 요소를 반환합니다.
## 비고



예: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)