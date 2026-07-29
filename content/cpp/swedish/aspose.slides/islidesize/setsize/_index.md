---
title: SetSize()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in bildstorleken efter typ och skalar befintligt innehåll. Att tilldela vilket värde som helst förutom SlideSizeType::Custom justerar ISlideSize::get_Size baserat på den valda typen, samtidigt som ISlideSize::get_Orientation bevaras."
type: docs
weight: 53
url: /sv/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metod

Ställer in bildstorleken efter typ och skalar befintligt innehåll. Att tilldela något annat värde än [SlideSizeType::Custom](../../slidesizetype/) justerar [ISlideSize::get_Size](../get_size/) baserat på den valda typen, samtidigt som [ISlideSize::get_Orientation](../get_orientation/) bevaras.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Den fördefinierade bildstorleken att använda. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Innehållsskaleringsläget att använda. |

## Anmärkningar

Att tilldela något annat värde än [SlideSizeType::Custom](../../slidesizetype/) justerar [System::Drawing::Size](../../../system.drawing/size/) baserat på den valda typen, samtidigt som [Orientation](../../orientation/) bevaras.

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metod

Ställer in bildens dimensioner explicit och skalar befintligt innehåll. Detta återställer värdet [ISlideSize::get_Type](../get_type/) till [SlideSizeType::Custom](../../slidesizetype/) och sätter [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | **float** | Den nya bildbredden i punkter. |
| height | **float** | Den nya bildhöjden i punkter. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Innehållsskaleringsläget att använda. |

## Anmärkningar

Detta återställer egenskapen [ISlideSize::get_Type](../get_type/) till [SlideSizeType::Custom](../../slidesizetype/) och sätter [Orientation](../../orientation/).

## Se även

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)