---
title: MathAccent()
second_title: C++용 Aspose.Slides API 참조
description: 기본 악센트 문자 값을 사용하여 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) 생성자

기본 악센트 문자값을 사용하여 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다.

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 악센트를 적용할 수학 요소 |
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) 생성자

지정된 수학 요소에 적용되는 수학 악센트를 생성합니다.

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 악센트를 적용할 수학 요소 |
| accentCharacter | char16_t | 악센트 문자 |
## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)