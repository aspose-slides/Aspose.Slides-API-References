---
title: FindShape()
second_title: Справочник API Aspose.Slides для C++
description: Найдите фигуру по альтернативному тексту в презентации PPTX.
type: docs
weight: 1
url: /ru/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) метод


Найти фигуру по альтернативному тексту в презентации PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Сканированная презентация. |
| altText | [System::String](../../../system/string/) | Альтернативный текст фигуры. |

### Return Value

[Shape](../../../aspose.slides/shape/) or null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) метод


Найти фигуру по альтернативному тексту на слайде в презентации PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Сканированный слайд. |
| altText | [System::String](../../../system/string/) | Альтернативный текст фигуры. |

### Return Value

[Shape](../../../aspose.slides/shape/) or null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)