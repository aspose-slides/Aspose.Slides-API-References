---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 슬라이드에서 지정된 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다.
type: docs
weight: 66
url: /ko/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) 메서드


지정된 슬라이드에서 지정된 텍스트를 포함하는 모든 텍스트 프레임을 반환합니다.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 검색할 슬라이드. |
| text | [System::String](../../../system/string/) | 텍스트 프레임 내에서 검색할 텍스트. |
| checkPlaceholderText | **bool** | 비어 있지만 자리 표시자 텍스트에 검색 텍스트가 포함된 텍스트 프레임을 포함할지 여부를 나타냅니다. |

### 반환 값

지정된 텍스트를 포함하는 [ITextFrame](../../../aspose.slides/itextframe/) 객체 배열.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)