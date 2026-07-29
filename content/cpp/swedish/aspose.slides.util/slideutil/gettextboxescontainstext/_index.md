---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alla textramar på den angivna bilden som innehåller den givna texten.
type: docs
weight: 66
url: /sv/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) metod


Returnerar alla textramar på den angivna bilden som innehåller den givna texten.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Bilden att söka i. |
| text | [System::String](../../../system/string/) | Texten att söka efter i textramar. |
| checkPlaceholderText | **bool** | Anger huruvida textramar som är tomma men vars platshållartext innehåller söktexten ska inkluderas. |

### Returvärde

En array av [ITextFrame](../../../aspose.slides/itextframe/)-objekt som innehåller den angivna texten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)