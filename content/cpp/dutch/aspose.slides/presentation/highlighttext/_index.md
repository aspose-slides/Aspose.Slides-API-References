---
title: HighlightText()
second_title: Aspose.Slides voor C++ API-referentie
description: Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.
type: docs
weight: 495
url: /nl/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) methode

Markeert alle overeenkomstige exemplaren van de voorbeeldtekst met de opgegeven kleur.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |

## Opmerkingen

Het volgende codevoorbeeld toont hoe tekst gemarkeerd kan worden in een PowerPoint-presentatie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// markeren van alle afzonderlijke 'the' voorkomens
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) methode

Markeert alle overeenkomstige exemplaren van de voorbeeldtekst met de opgegeven kleur.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstopzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |

## Opmerkingen

Het volgende codevoorbeeld toont hoe tekst gemarkeerd kan worden in een PowerPoint-presentatie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// markeren van alle afzonderlijke 'the' voorkomens
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [Presentation](../)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)