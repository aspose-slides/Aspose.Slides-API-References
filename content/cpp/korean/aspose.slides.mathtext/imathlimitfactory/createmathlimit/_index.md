---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: IMathLimit을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) 메서드

생성합니다 [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한을 적용할 기본 인수 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한 요소 |
| upperLimit | **bool** | 제한을 위에 배치하도록 설정합니다 |

### 반환값

새 수학 제한

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드

하단에 제한이 있는 [IMathLimit](../../imathlimit/)를 생성합니다

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한을 적용할 기본 인수 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한 요소 |

### 반환값

새 수학 제한

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLimit](../../imathlimit/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathLimitFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)