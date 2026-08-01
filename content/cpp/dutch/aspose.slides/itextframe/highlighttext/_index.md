---
title: HighlightText()
second_title: Aspose.Slides voor C++ API Referentie
description: Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.
type: docs
weight: 105
url: /nl/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) methode


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) methode


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Markeeropties. |

Verouderd
:   Gebruik in plaats daarvan de methode HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback). De methode zal worden verwijderd na de release van versie 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) methode


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | De tekst om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende codevoorbeeld toont hoe u tekst kunt markeren in een [TextFrame](../../textframe/). 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)