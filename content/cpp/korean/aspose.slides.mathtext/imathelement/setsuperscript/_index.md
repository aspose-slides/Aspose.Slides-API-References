---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API 참조
description: 위첨자를 생성합니다
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) method


위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 위첨자(오른쪽 위 인덱스) |

### 반환 값

새로운 수학 요소 타입 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 참고



예시: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) method


위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 위첨자(오른쪽 위 인덱스) |

### 반환 값

새로운 수학 요소 타입 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 참고



예시: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)