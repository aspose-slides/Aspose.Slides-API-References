---
title: Nary()
second_title: Aspose.Slides for C++ API 레퍼런스
description: N-ary 연산자를 생성합니다
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

N-ary 연산자를 생성합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary 연산자 유형 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 상한 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) 메서드

N-ary 연산자를 생성합니다

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary 연산자 유형 |
| lowerLimit | [System::String](../../../system/string/) | 하한 |
| upperLimit | [System::String](../../../system/string/) | 상한 |

### 반환 값

새 인스턴스 유형 [IMathNaryOperator](../../imathnaryoperator/)
## 비고



예시: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## 관련 항목

* 열거형 [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathNaryOperator](../../imathnaryoperator/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)