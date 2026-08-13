---
title: Delimit()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 구분자 문자를 사용하여 인수를 구분합니다
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) 메서드

지정된 구분자 문자를 사용하여 인수를 구분합니다

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char16_t | 구분자 문자 |

### 반환값

구분자 문자를 적용한 후의 객체

## 비고

예시:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)