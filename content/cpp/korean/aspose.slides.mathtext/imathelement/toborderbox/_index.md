---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 요소를 경계 상자에 배치합니다
type: docs
weight: 261
url: /ko/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() 메서드

이 요소를 경계 상자에 배치합니다.

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### 반환 값

이 요소가 내부에 배치된 경계 상자

## 비고



예시: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) 메서드

이 요소를 경계 상자에 배치합니다.

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hideTop | **bool** | 위 가장자리 숨기기 |
| hideBottom | **bool** | 아래 가장자리 숨기기 |
| hideLeft | **bool** | 왼쪽 가장자리 숨기기 |
| hideRight | **bool** | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 경계 상자 수평 취소선 |
| strikethroughVertical | **bool** | 경계 상자 수직 취소선 |
| strikethroughBottomLeftToTopRight | **bool** | 경계 상자 왼쪽 아래에서 오른쪽 위로 취소선 |
| strikethroughTopLeftToBottomRight | **bool** | 경계 상자 왼쪽 위에서 오른쪽 아래로 취소선 |

### 반환 값

이 요소가 내부에 배치된 경계 상자

## 비고



```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)