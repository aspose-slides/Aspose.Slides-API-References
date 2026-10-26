---
title: ReplaceRegex()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle overeenkomsten van reguliere expressie met opgegeven tekenreeks.
type: docs
weight: 183
url: /nl/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method


Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | De reguliere expressie [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) om de te vervangen tekenreeksen te verkrijgen. |
| newText | [System::String](../../../system/string/) | De tekenreeks om alle voorkomens van te vervangen tekenreeksen te vervangen. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-object voor het opslaan van het resultaat van de vervangingsbewerking [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende voorbeeldcode laat zien hoe tekst te vervangen met een reguliere expressie en een opgegeven tekenreeks. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [String](../../../system/string/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [TextFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)