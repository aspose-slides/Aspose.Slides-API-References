---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수 이름 |

### 반환값

새 수학 요소 타입 [IMathFunction](../../imathfunction/)
## 참고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | 함수 이름 |

### 반환값

새 수학 요소 타입 [IMathFunction](../../imathfunction/)
## 참고



예: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 호출합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 인수가 하나인 일반적인 함수 유형 중 하나 |

### 반환값

새 수학 요소 타입 [IMathFunction](../../imathfunction/)
## 참고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 호출하고 추가 인수를 지정합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 인수가 두 개인 일반적인 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수 유형에 따라 달라지는 추가 인수 |

### 반환값

새 수학 요소 타입 [IMathFunction](../../imathfunction/)
## 참고



예: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x'의 로그를 밑 '5'로 반환합니다
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 호출하고 추가 인수를 지정합니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### 인수

| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 인수가 두 개인 일반적인 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | 함수 유형에 따라 달라지는 추가 인수 |

### 반환값

새 수학 요소 타입 [IMathFunction](../../imathfunction/)
## 참고



예: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x'의 로그를 밑 '5'로 반환합니다
```

## 참조

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFunction](../../imathfunction/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)