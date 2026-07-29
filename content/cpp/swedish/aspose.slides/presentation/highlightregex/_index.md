---
title: HighlightRegex()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla matchningar av det reguljära uttrycket med den angivna färgen.
type: docs
weight: 508
url: /sv/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metod


Markerar alla matchningar av det reguljära uttrycket med den angivna färgen.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Det reguljära uttrycket [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att få strängar att markeras. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar



Följande kodexempel visar hur man markerar text i en PowerPoint [Presentation](../) med hjälp av ett reguljärt uttryck. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [Color](../../../system.drawing/color/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)