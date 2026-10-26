---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하한을 설정합니다
type: docs
weight: 157
url: /ko/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) method

하한을 설정합니다

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### 반환 값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)
## 비고



예:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) method

하한을 설정합니다

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 반환 값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)
## 비고



예:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLimit](../../imathlimit/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)