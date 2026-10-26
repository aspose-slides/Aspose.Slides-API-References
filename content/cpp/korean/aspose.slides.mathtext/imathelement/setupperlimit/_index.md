---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상한값을 지정합니다
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) 메서드


상한값을 지정합니다

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) 메서드


상한값을 지정합니다

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLimit](../../imathlimit/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)