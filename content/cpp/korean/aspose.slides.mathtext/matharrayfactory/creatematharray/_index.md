---
title: CreateMathArray()
second_title: Aspose.Slides for C++ API 참조
description: 수학 배열을 생성하고 지정된 요소를 배열에 배치합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/matharrayfactory/creatematharray/
---
## MathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElement\>) 메서드

수학 배열을 생성하고 지정된 요소를 배열에 배치합니다

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathArrayFactory::CreateMathArray(System::SharedPtr<IMathElement> element) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 배열에 배치할 수학 요소 |

### 반환값

새 수학 배열

## MathArrayFactory::CreateMathArray(System::SharedPtr\<IMathElementCollection\>) 메서드

수학 배열을 생성하고 지정된 요소들을 배열에 배치합니다

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathArrayFactory::CreateMathArray(System::SharedPtr<IMathElementCollection> elements) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 배열에 배치할 수학 요소들 |

### 반환값

새 수학 배열

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathArray](../../imatharray/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathArrayFactory](../)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)