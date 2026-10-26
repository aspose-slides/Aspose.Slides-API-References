---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소에 적용하여 수학 테두리 상자를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

요소에 적용하여 수학 테두리 상자를 생성합니다

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 테두리 상자를 적용할 수학 요소 |
| hideTop | **bool** | 상단 가장자리 숨기기 |
| hideBottom | **bool** | 하단 가장자리 숨기기 |
| hideLeft | **bool** | 좌측 가장자리 숨기기 |
| hideRight | **bool** | 우측 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 가로 취소선 테두리 상자 |
| strikethroughVertical | **bool** | 세로 취소선 테두리 상자 |
| strikethroughBottomLeftToTopRight | **bool** | 좌하단에서 우상단까지의 취소선 테두리 상자 |
| strikethroughTopLeftToBottomRight | **bool** | 좌상단에서 우하단까지의 취소선 테두리 상자 |

### Return Value

새 테두리 상자 요소

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

요소에 적용하여 수학 테두리 상자를 생성합니다

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 테두리 상자를 적용할 수학 요소 |
| hideTop | **bool** | 상단 가장자리 숨기기 |
| hideBottom | **bool** | 하단 가장자리 숨기기 |
| hideLeft | **bool** | 좌측 가장자리 숨기기 |
| hideRight | **bool** | 우측 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 가로 취소선 테두리 상자 |
| strikethroughVertical | **bool** | 세로 취소선 테두리 상자 |
| strikethroughBottomLeftToTopRight | **bool** | 좌하단에서 우상단까지의 취소선 테두리 상자 |
| strikethroughTopLeftToBottomRight | **bool** | 좌상단에서 우하단까지의 취소선 테두리 상자 |

### Return Value

새 테두리 상자 요소

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBorderBox](../../imathborderbox/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathBorderBoxFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)