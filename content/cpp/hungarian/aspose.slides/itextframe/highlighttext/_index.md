---
title: HighlightText()
second_title: Aspose.Slides for C++ API-referencia
description: Kiemeli a mintaszöveg összes előfordulását a megadott színnel.
type: docs
weight: 105
url: /hu/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) method


Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használandó szín. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használandó szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | A kiemelés beállításai. |

Elavult
:   Használja helyette a HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) metódust. A metódus a 24.10-es verzió kiadása után kerül eltávolításra.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | A kiemelendő szöveg. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használandó szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | A szövegkeresés beállításai [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../ifindresultcallback/). |

## Megjegyzések



A következő kódminta bemutatja, hogyan lehet szöveget kiemelni egy [TextFrame](../../textframe/)-ben. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [ITextFrame](../)
* Osztály [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)