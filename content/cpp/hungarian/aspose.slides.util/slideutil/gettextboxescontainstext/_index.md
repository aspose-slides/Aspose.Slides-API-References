---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az adott dián az összes szövegkeretet, amelyek tartalmazzák a megadott szöveget.
type: docs
weight: 66
url: /hu/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) metódus

Visszaadja a megadott dián az összes szövegkeretet, amelyek tartalmazzák az adott szöveget.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | A keresendő dia. |
| text | [System::String](../../../system/string/) | A szövegkeretekben keresendő szöveg. |
| checkPlaceholderText | **bool** | Jelzi, hogy be kell-e vonni a szövegkereteket, amelyek üresek, de a helykitöltő szövegük tartalmazza a keresett szöveget. |

### Visszatérési érték

Egy [ITextFrame](../../../aspose.slides/itextframe/) objektumok tömbje, amelyek tartalmazzák a megadott szöveget.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITextFrame](../../../aspose.slides/itextframe/)
* Osztály [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Osztály [String](../../../system/string/)
* Osztály [SlideUtil](../)
* Névtér [Aspose::Slides::Util](../../)
* Könyvtár [Aspose.Slides](../../../)