---
title: CreateMathArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 배열을 생성하고 지정된 요소를 배열에 배치합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imatharrayfactory/creatematharray/
---
## IMathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElement\>) 메서드


수학 배열을 생성하고 지정된 요소를 배열에 배치합니다

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathArrayFactory::CreateMathArray(System::SharedPtr<IMathElement> element)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 배열에 배치할 수학 요소 |

### 반환 값

새 수학 배열

## IMathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElementCollection\>) 메서드


수학 배열을 생성하고 지정된 요소들을 배열에 배치합니다

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathArrayFactory::CreateMathArray(System::SharedPtr<IMathElementCollection> elements)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 배열에 배치할 수학 요소들 |

### 반환 값

새 수학 배열

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathArray](../../imatharray/)
* Class [IMathElement](../../imathelement/)
* Class [IMathArrayFactory](../)
* Class [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)