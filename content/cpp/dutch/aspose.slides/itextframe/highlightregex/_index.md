---
title: HighlightRegex()
second_title: Aspose.Slides voor C++ API-referentie
description: Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.
type: docs
weight: 131
url: /nl/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | De reguliere expressie [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) om strings te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen

De volgende code-voorbeeld toont hoe tekst te markeren in een [TextFrame](../../textframe/) met behulp van een reguliere expressie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// markeren van alle woorden met 10 of meer tekens
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Tekst van de reguliere expressie om tekst te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Markeeropties. |

Verouderd
:   Gebruik in plaats daarvan de HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) methode. De methode wordt verwijderd na de release van versie 24.10.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [ITextFrame](../)
* Klasse [String](../../../system/string/)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)