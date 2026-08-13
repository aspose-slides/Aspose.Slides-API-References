---
title: SetSubscript()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 첨자를 생성합니다
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) 메서드

첨자를 생성합니다

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 첨자 (오른쪽 아래 인덱스) |

### 반환값

새 수학 요소 유형 [IMathSubscriptElement](../../imathsubscriptelement/)

## 비고



예시: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) 메서드

첨자를 생성합니다

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 첨자 (오른쪽 아래 인덱스) |

### 반환값

새 수학 요소 유형 [IMathSubscriptElement](../../imathsubscriptelement/)

## 비고



예시: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathSubscriptElement](../../imathsubscriptelement/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)