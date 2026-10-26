---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 요소를 경계 상자에 배치합니다
type: docs
weight: 248
url: /ko/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() 메서드

이 요소를 경계 상자에 배치합니다

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### 반환 값

이 요소가 내부에 배치된 경계 상자

## 비고



예: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) 메서드

이 요소를 경계 상자에 배치합니다

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hideTop | **bool** | 상단 가장자리 숨기기 |
| hideBottom | **bool** | 하단 가장자리 숨기기 |
| hideLeft | **bool** | 왼쪽 가장자리 숨기기 |
| hideRight | **bool** | 오른쪽 가장자리 숨기기 |
| strikethroughHorizontal | **bool** | 가로 취소선 경계 상자 |
| strikethroughVertical | **bool** | 세로 취소선 경계 상자 |
| strikethroughBottomLeftToTopRight | **bool** | 좌하단에서 우상단으로 취소선 경계 상자 |
| strikethroughTopLeftToBottomRight | **bool** | 좌상단에서 우하단으로 취소선 경계 상자 |

### 반환 값

이 요소가 내부에 배치된 경계 상자

## 비고



예: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBorderBox](../../imathborderbox/)
* 클래스 [MathElementBase](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)