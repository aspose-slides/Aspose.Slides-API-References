---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API 참조
description: 위첨자를 생성합니다
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) 메서드

위첨자를 생성합니다

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 위첨자 (오른쪽에 위에 위치) |

### 반환값

새 수학 요소 유형 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) 메서드

위첨자를 생성합니다

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 위첨자 (오른쪽에 위에 위치) |

### 반환값

새 수학 요소 유형 [IMathSuperscriptElement](../../imathsuperscriptelement/)
## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathSuperscriptElement](../../imathsuperscriptelement/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)