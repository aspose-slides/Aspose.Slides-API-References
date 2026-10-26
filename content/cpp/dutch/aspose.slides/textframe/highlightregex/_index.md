---
title: HighlightRegex()
second_title: Aspose.Slides voor C++ API-referentie
description: Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.
type: docs
weight: 157
url: /nl/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Tekst van reguliere expressie om te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Markeeropties. |

## Opmerkingen

Verouderd
:   Gebruik in plaats daarvan de methode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). De methode wordt verwijderd na de release van versie 24.10.

De volgende codevoorbeeld toont hoe tekst te markeren in een [TextFrame](../) met behulp van een reguliere expressie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// markeren van alle woorden met 10 of meer tekens
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | De reguliere expressie [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) om strings te markeren. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |

## Opmerkingen

De volgende codevoorbeeld toont hoe tekst te markeren in een [TextFrame](../) met behulp van een reguliere expressie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// markeren van alle woorden met 10 of meer tekens
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klasse [TextFrame](../)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)