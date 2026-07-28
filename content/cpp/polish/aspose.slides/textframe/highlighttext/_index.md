---
title: HighlightText()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Podświetla wszystkie wystąpienia próbki tekstu przy użyciu określonego koloru.
type: docs
weight: 131
url: /pl/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) metoda


Podświetla wszystkie wystąpienia próbki tekstu przy użyciu określonego koloru.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Próbka tekstu do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda


Podświetla wszystkie wystąpienia próbki tekstu przy użyciu określonego koloru.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opcje podświetlania. |
## Uwagi


Przestarzałe
:   Użyj metody HighlightText(string text, Color highlightColor, ITextSearchOptions options) zamiast tego. Metoda zostanie usunięta po wydaniu wersji 24.10.


Poniższy kod przykładowy pokazuje, jak podświetlić tekst w [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda


Podświetla wszystkie wystąpienia próbki tekstu przy użyciu określonego koloru.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opcje wyszukiwania tekstu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi



Poniższy przykład kodu pokazuje, jak podświetlić tekst w [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// podświetlanie wszystkich słów 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// podświetlanie wszystkich oddzielnych wystąpień 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [TextFrame](../)
* Klasa [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klasa [ITextSearchOptions](../../itextsearchoptions/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)