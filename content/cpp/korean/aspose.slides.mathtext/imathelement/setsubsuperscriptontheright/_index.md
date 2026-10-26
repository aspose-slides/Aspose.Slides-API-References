---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API 참조
description: 오른쪽에 아래첨자와 위첨자를 생성합니다
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

오른쪽에 아래첨자와 위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 아래첨자 (오른쪽에 위치한 아래 인덱스) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 위첨자 (오른쪽에 위치한 위 인덱스) |

### 반환값

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) method

오른쪽에 아래첨자와 위첨자를 생성합니다

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 아래첨자 (오른쪽에 위치한 아래 인덱스) |
| superscript | [System::String](../../../system/string/) | 위첨자 (오른쪽에 위치한 위 인덱스) |

### 반환값

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## 비고



예시: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* 클래스 [IMathElement](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)