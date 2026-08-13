---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하한을 입력합니다
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) 메서드

하한을 입력합니다

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한 |

### 반환값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)

## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) 메서드

하한을 입력합니다

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | 제한 |

### 반환값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)

## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLimit](../../imathlimit/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)