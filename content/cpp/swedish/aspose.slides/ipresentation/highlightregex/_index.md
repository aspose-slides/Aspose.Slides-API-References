---
title: HighlightRegex()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla matchningar av det reguljära uttrycket med den angivna färgen.
type: docs
weight: 469
url: /sv/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Markerar alla matchningar av det reguljära uttrycket med den angivna färgen.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Det reguljära uttrycket [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att få strängar att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar



Följande kodexempel visar hur man markerar text i en PowerPoint [Presentation](../../presentation/) med ett reguljärt uttryck. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// markerar alla ord med 10 eller fler tecken
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [Color](../../../system.drawing/color/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [IPresentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)