---
title: Radical()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 인수에서 주어진 차수에 대한 수학적 루트를 지정합니다.
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) 메서드


주어진 차수에 대한 수학적 루트를 지정된 인수에서 구합니다.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Radical의 인수 |

### 반환 값

새 인스턴스 유형 [IMathRadical](../../imathradical/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) 메서드


주어진 차수에 대한 수학적 루트를 지정된 인수에서 구합니다.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical의 인수 |

### 반환 값

새 인스턴스 유형 [IMathRadical](../../imathradical/)
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathRadical](../../imathradical/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)