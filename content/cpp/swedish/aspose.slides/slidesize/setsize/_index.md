---
title: SetSize()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in bildstorleken efter typ och skalar befintligt innehåll.
type: docs
weight: 53
url: /sv/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metod


Ställer in bildstorleken efter typ och skalar befintligt innehåll.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Anmärkningar


Att tilldela något annat värde än [SlideSizeType::Custom](../../slidesizetype/) justerar [SlideSize::get_Size](../get_size/) baserat på den valda typen, samtidigt som [SlideSize::get_Orientation](../get_orientation/) bevaras. 

## SlideSize::SetSize(float, float, SlideSizeScaleType) metod


Ställer in bildens dimensioner explicit och skalar befintligt innehåll.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | **float** | Den nya bildbredden, i punkter. |
| height | **float** | Den nya bildhöjden, i punkter. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Det skalningsläge för innehåll som ska användas. |
## Anmärkningar


Detta återställer egenskapen [SlideSize::get_Type](../get_type/) till [SlideSizeType::Custom](../../slidesizetype/) och sätter [Orientation](../../orientation/). 

## Se även

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klass [SlideSize](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)