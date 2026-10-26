---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소에 적용하여 수학 경계 상자를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) 메서드

요소에 적용하여 수학 경계 상자를 생성합니다

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 경계 상자를 적용할 수학 요소 |

### 반환값

새 경계 상자 요소

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 메서드

요소에 적용하여 수학 경계 상자를 생성합니다

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 경계 상자를 적용할 수학 요소 |
| hideTop | **bool** | 상단 가장자리 숨기기 |
| hideBottom | **bool** | 하단 가장자리 숨기기 |
| hideLeft | **bool** | 왼쪽 가장자리 숨기기 |
| hideRight | **bool** | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 경계 상자 가로 취소선 |
| strikethroughVertical | **bool** | 경계 상자 세로 취소선 |
| strikethroughBottomLeftToTopRight | **bool** | 경계 상자 왼쪽 하단에서 오른쪽 상단으로 취소선 |
| strikethroughTopLeftToBottomRight | **bool** | 경계 상자 왼쪽 상단에서 오른쪽 하단으로 취소선 |

### 반환값

새 경계 상자 요소

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBorderBox](../../imathborderbox/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBorderBoxFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)