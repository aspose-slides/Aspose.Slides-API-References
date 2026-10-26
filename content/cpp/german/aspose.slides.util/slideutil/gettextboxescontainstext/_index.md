---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt alle Textfelder auf der angegebenen Folie zurück, die den angegebenen Text enthalten.
type: docs
weight: 66
url: /de/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) Methode

Gibt alle Textfelder auf der angegebenen Folie zurück, die den angegebenen Text enthalten.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Die Folie, die durchsucht werden soll. |
| text | [System::String](../../../system/string/) | Der Text, nach dem innerhalb von Textfeldern gesucht wird. |
| checkPlaceholderText | **bool** | Gibt an, ob leere Textfelder einbezogen werden sollen, deren Platzhaltertext den Suchtext enthält. |

### Rückgabewert

Ein Array von [ITextFrame](../../../aspose.slides/itextframe/)-Objekten, die den angegebenen Text enthalten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../../aspose.slides/itextframe/)
* Klasse [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klasse [String](../../../system/string/)
* Klasse [SlideUtil](../)
* Namensraum [Aspose::Slides::Util](../../)
* Bibliothek [Aspose.Slides](../../../)