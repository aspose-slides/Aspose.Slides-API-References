---
title: Function()
second_title: Aspose.Slides for C++ API 참조
description: 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 가져옵니다
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) 메서드


이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 가져옵니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 함수의 인수 |

### Return Value

새 수학 요소 유형 [IMathFunction](../../imathfunction/)
## 비고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) 메서드


이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 가져옵니다

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | 함수의 인수 |

### Return Value

새 수학 요소 유형 [IMathFunction](../../imathfunction/)
## 비고



예: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathFunction](../../imathfunction/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)