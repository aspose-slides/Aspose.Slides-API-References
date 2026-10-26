---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오른쪽에 아래 첨자와 위 첨자를 생성합니다
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 메서드


Creates subscript and superscript on the right

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 아래 첨자 (오른쪽에 있는 하위 인덱스) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 위 첨자 (오른쪽에 있는 상위 인덱스) |

### 반환 값

새 수학 요소 유형 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) 메서드


Creates subscript and superscript on the right

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 아래 첨자 (오른쪽에 있는 하위 인덱스) |
| superscript | [System::String](../../../system/string/) | 위 첨자 (오른쪽에 있는 상위 인덱스) |

### 반환 값

새 수학 요소 유형 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## 비고



예제: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)