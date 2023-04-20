---
title: FindShape()
second_title: Aspose.Slides for C++ API Reference
description: Find shape by alternative text in a PPTX presentation.
type: docs
weight: 1
url: /cpp/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method


Find shape by alternative text in a PPTX presentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Scanned presentation. |
| altText | [System::String](../../../system/string/) | Alternative text of a shape. |

### Return Value

[Shape](../../../aspose.slides/shape/) or null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method


Find shape by alternative text on a slide in a PPTX presentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Scanned slide. |
| altText | [System::String](../../../system/string/) | Alternative text of a shape. |

### Return Value

[Shape](../../../aspose.slides/shape/) or null.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)