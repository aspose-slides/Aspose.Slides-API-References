---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API 참조
description: 수학 함수를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

수학 함수를 생성합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수 이름으로 사용되는 요소 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수 인수로 사용되는 요소 |

### 반환값

새 수학 함수

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) 메서드

수학 함수를 생성합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 함수 이름 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수 인수로 사용되는 요소 |

### 반환값

새 수학 함수

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFunction](../../imathfunction/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathFunctionFactory](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)