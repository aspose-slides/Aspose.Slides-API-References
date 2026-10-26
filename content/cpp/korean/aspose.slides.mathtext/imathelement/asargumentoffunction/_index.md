---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 인스턴스를 인수로 사용하여 지정된 함수를 수행합니다
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 수행합니다.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 함수 이름 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)

## 비고

예:
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 수행합니다.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | 함수 이름 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)

## 비고

예:
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) 메서드

이 인스턴스를 인수로 사용하여 지정된 함수를 수행합니다.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | 하나의 인수를 갖는 일반 함수 유형 중 하나 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)

## 비고

예:
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) 메서드

이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 수행합니다.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 두 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 함수 유형에 따라 달라지는 추가 인수 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)

## 비고

예:
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x'의 로그를 밑 '5'로 반환합니다
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) 메서드

이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 수행합니다.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | 두 인수를 갖는 일반 함수 유형 중 하나: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | 함수 유형에 따라 달라지는 추가 인수 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)

## 비고

예:
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x'의 로그를 밑 '5'로 반환합니다
```

## 참고

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)