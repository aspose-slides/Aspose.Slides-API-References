---
title: HighlightRegex()
second_title: Aspose.Slides voor de C++ API-referentie
description: Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.
type: docs
weight: 508
url: /nl/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | De reguliere expressie [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) om de te markeren tekenreeksen te verkrijgen. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | De kleur om de tekst te markeren. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende codevoorbeeld toont hoe u tekst in een PowerPoint [Presentation](../) kunt markeren met behulp van een reguliere expressie. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)