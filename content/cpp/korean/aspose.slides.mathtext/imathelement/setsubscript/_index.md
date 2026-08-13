---
title: SetSubscript()
second_title: Aspose.Slides for C++ API 참조
description: 첨자를 생성합니다
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) method

첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 첨자(오른쪽에 하위 인덱스) |

### 반환값

새 수학 요소 유형 [IMathSubscriptElement](../../imathsubscriptelement/)
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) method

첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 첨자(오른쪽에 하위 인덱스) |

### 반환값

새 수학 요소 유형 [IMathSubscriptElement](../../imathsubscriptelement/)
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathSubscriptElement](../../imathsubscriptelement/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)