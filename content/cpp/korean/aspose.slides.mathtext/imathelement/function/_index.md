---
title: Function()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) 메서드

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 함수의 인수 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)
## 비고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) 메서드

이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 함수의 인수 |

### 반환 값

새 수학 요소 유형 [IMathFunction](../../imathfunction/)
## 비고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFunction](../../imathfunction/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)