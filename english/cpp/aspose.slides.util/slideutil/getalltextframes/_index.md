---
title: GetAllTextFrames()
second_title: Aspose.Slides for C++ API Reference
description: Returns all text frames in a PPTX presentation.
type: docs
weight: 53
url: /cpp/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames([System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\>, **bool**) method


Returns all text frames in a PPTX presentation.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Scanned presentation. |
| withMasters | **bool** | Determines whether master slides should be scanned. |

### Return Value

Array of [TextFrame](../../../aspose.slides/textframe/) objects.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)
