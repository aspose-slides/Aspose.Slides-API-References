---
title: CreateMathNaryOperator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IMathNaryOperator를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathnaryoperatorfactory/createmathnaryoperator/
---
## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

생성합니다 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |

### 반환값

새로운 [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

생성합니다 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |

### 반환값

새로운 [IMathNaryOperator](../../imathnaryoperator/)

## MathNaryOperatorFactory::CreateMathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) 메서드

생성합니다 [IMathNaryOperator](../../imathnaryoperator/)

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathNaryOperatorFactory::CreateMathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | The operator sign |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply operator |

### 반환값

새로운 [IMathNaryOperator](../../imathnaryoperator/)

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathNaryOperator](../../imathnaryoperator/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathNaryOperatorFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)