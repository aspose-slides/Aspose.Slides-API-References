---
title: HighlightText()
second_title: Aspose.Slides C++ API referenciája
description: Kiemeli a mintaszöveg összes előfordulását a megadott színnel.
type: docs
weight: 131
url: /hu/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) metódus

Kiemeli a minta szöveg minden előfordulását a megadott színnel.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg minta. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metódus

Kiemeli a minta szöveg minden előfordulását a megadott színnel.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Kiemelési beállítások. |

## Megjegyzések

Elavult: Használja helyette a HighlightText(string text, Color highlightColor, ITextSearchOptions options) metódust. A metódus a 24.10-es verzió kiadása után eltávolításra kerül.

Az alábbi példa kód megmutatja, hogyan kell kiemelni a szöveget egy [TextFrame](../)-ban. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// az összes 'important' szó kiemelése
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// az összes különálló 'the' előfordulás kiemelése
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus

Kiemeli a minta szöveg minden előfordulását a megadott színnel.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../ifindresultcallback/). |

## Megjegyzések



Az alábbi kódminta megmutatja, hogyan kell kiemelni a szöveget egy [TextFrame](../)-ban. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// az összes 'important' szó kiemelése
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// az összes különálló 'the' előfordulás kiemelése
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [TextFrame](../)
* Osztály [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)