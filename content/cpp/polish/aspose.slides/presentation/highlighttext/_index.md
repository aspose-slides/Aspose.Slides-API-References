---
title: HighlightText()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Podświetla wszystkie dopasowania tekstu przykładowego określonym kolorem.
type: docs
weight: 495
url: /pl/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metoda

Podświetla wszystkie dopasowania tekstu wzorcowego określonym kolorem.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor podświetlenia tekstu. |
## Uwagi

Poniższy przykład kodu pokazuje, jak podświetlić tekst w prezentacji PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// podświetlanie wszystkich oddzielnych wystąpień 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda

Podświetla wszystkie dopasowania tekstu wzorcowego określonym kolorem.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor podświetlenia tekstu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opcje wyszukiwania tekstu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi

Poniższy przykład kodu pokazuje, jak podświetlić tekst w prezentacji PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// podświetlanie wszystkich oddzielnych wystąpień 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [Presentation](../)
* Klasa [ITextSearchOptions](../../itextsearchoptions/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)