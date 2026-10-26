---
title: Radical()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인수에서 주어진 차수에 대한 수학적 루트를 지정합니다.
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) method


지정된 인수에서 주어진 차수에 대한 수학적 루트를 지정합니다.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 루트 인수 |

### 반환 값

새 인스턴스 형식 [IMathRadical](../../imathradical/)
## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) method


지정된 인수에서 주어진 차수에 대한 수학적 루트를 지정합니다.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | 루트 인수 |

### 반환 값

새 인스턴스 형식 [IMathRadical](../../imathradical/)
## 비고



예: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathRadical](../../imathradical/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)