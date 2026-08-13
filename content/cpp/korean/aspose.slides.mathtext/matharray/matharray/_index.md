---
title: MathArray()
second_title: Aspose.Slides for C++ API 참조
description: 수학 배열을 생성하고 지정된 요소를 배열에 배치합니다.
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) 생성자


수학 배열을 생성하고 지정된 요소를 배열에 배치합니다.

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 배열에 배치할 요소 |
## 비고



예제: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) 생성자


수학 배열을 생성하고 지정된 요소들을 배열에 배치합니다.

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | 배열에 배치할 요소들 |

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathArray](../)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)