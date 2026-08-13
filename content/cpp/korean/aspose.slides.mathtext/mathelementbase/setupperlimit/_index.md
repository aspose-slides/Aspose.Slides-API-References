---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상한을 지정합니다
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) 메서드


상한을 지정합니다

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 제한 |

### 반환값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) 메서드


상한을 지정합니다

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | 제한 |

### 반환값

새 인스턴스 유형 [IMathLimit](../../imathlimit/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathLimit](../../imathlimit/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)