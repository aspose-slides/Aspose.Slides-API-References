---
title: Join()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 요소를 결합하여 수학 블록을 형성합니다
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) 메서드


수학 요소를 결합하여 수학 블록을 형성합니다

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 결합될 요소 |

### 반환 값

이 인스턴스와 지정된 인수를 포함하는 새 [IMathBlock](../../imathblock/)

## 비고



예제: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) 메서드


수학 텍스트를 결합하여 수학 블록을 형성합니다

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 결합될 수학 텍스트 |

### 반환 값

이 인스턴스와 지정된 인수를 포함하는 새 [IMathBlock](../../imathblock/)

## 비고



예제: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)