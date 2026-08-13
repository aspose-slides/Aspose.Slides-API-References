---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API 참조
description: 왼쪽에 아래첨자와 위첨자를 생성합니다
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

왼쪽에 아래첨자와 위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 아래첨자 (왼쪽의 낮은 인덱스) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 위첨자 (왼쪽의 높은 인덱스) |

### 반환 값

새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## 비고

예:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) 메서드

왼쪽에 아래첨자와 위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 아래첨자 (왼쪽의 낮은 인덱스) |
| superscript | [System::String](../../../system/string/) | 위첨자 (왼쪽의 높은 인덱스) |

### 반환 값

새 수학 요소 유형 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## 비고

예:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)