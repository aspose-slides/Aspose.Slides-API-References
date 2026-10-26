---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací všechny textové rámy na zadaném snímku, které obsahují zadaný text.
type: docs
weight: 66
url: /cs/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) method

Vrací všechny textové rámy na zadaném snímku, které obsahují zadaný text.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Snímek, který se má prohledávat. |
| text | [System::String](../../../system/string/) | Text, který se má hledat v textových rámech. |
| checkPlaceholderText | **bool** | Určuje, zda zahrnout textové rámy, které jsou prázdné, ale jejich zástupný text obsahuje hledaný text. |

### Návratová hodnota

Pole objektů [ITextFrame](../../../aspose.slides/itextframe/), které obsahují zadaný text.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)