---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 직사각형 테두리를 가진 MathBorderBox 요소를 생성합니다
type: docs
weight: 222
url: /ko/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) constructor


[MathBorderBox](../) 요소를 직사각형 테두리와 함께 생성합니다

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 테두리 상자가 적용되는 기본 요소입니다. null일 수 있습니다. |
## 비고



예: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) constructor


[MathBorderBox](../) 요소를 생성합니다

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 테두리 상자가 적용되는 기본 요소 |
| hideTop | **bool** | 상단 가장자리 숨기기 |
| hideBottom | **bool** | 하단 가장자리 숨기기 |
| hideLeft | **bool** | 왼쪽 가장자리 숨기기 |
| hideRight | **bool** | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 수평 취소선 |
| strikethroughVertical | **bool** | 수직 취소선 |
| strikethroughBottomLeftToTopRight | **bool** | 왼쪽 아래에서 오른쪽 위까지 취소선 |
| strikethroughTopLeftToBottomRight | **bool** | 왼쪽 위에서 오른쪽 아래까지 취소선 |
## 비고



예: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)