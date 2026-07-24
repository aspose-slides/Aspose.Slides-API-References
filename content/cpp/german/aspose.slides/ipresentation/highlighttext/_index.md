---
title: HighlightText()
second_title: Aspose.Slides für C++ API-Referenz
description: Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.
type: docs
weight: 456
url: /de/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) Methode

Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu hervorhebende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |
## Bemerkungen

Das folgende Codebeispiel zeigt, wie Text in einer PowerPoint-Präsentation hervorgehoben wird. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) Methode

Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu hervorhebende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsuchoptionen [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Rückrufobjekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |
## Bemerkungen

Das folgende Codebeispiel zeigt, wie Text in einer PowerPoint-Präsentation hervorgehoben wird. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Hervorheben aller separaten 'the'-Vorkommen
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IPresentation](../)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)