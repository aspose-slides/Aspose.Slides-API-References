---
title: SetSubSuperscriptOnTheLeft()
second_title: C++용 Aspose.Slides API 참조
description: 왼쪽에 아래 첨자와 위 첨자를 생성합니다
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

왼쪽에 아래 첨자와 위 첨자를 생성합니다

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 아래 첨자 (왼쪽에 있는 하위 인덱스) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 위 첨자 (왼쪽에 있는 상위 인덱스) |

### 반환 값

새로운 수학 요소, 유형 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) 메서드


왼쪽에 아래 첨자와 위 첨자를 생성합니다

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 아래 첨자 (왼쪽에 있는 하위 인덱스) |
| superscript | [System::String](../../../system/string/) | 위 첨자 (왼쪽에 있는 상위 인덱스) |

### 반환 값

새로운 수학 요소, 유형 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)