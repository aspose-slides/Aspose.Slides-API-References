---
title: HighlightText()
second_title: Aspose.Slides voor C++ API-referentie
description: Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.
type: docs
weight: 456
url: /nl/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) methode

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
## Opmerkingen

De volgende codevoorbeeld toont hoe tekst te markeren in een PowerPoint-presentatie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// markeert alle afzonderlijke 'the' voorkomens
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) methode

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen

De volgende codevoorbeeld toont hoe tekst te markeren in een PowerPoint-presentatie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// markeert alle afzonderlijke 'the' voorkomens
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IPresentation](../)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)