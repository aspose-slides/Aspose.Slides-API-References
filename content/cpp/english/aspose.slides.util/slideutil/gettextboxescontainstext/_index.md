---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API Reference
description: Returns all text frames on the specified slide that contain the given text.
type: docs
weight: 66
url: /aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) method


Returns all text frames on the specified slide that contain the given text.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | The slide to search. |
| text | [System::String](../../../system/string/) | The text to search for within text frames. |
| checkPlaceholderText | **bool** | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |

### Return Value

An array of [ITextFrame](../../../aspose.slides/itextframe/) objects that contain the specified text.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)