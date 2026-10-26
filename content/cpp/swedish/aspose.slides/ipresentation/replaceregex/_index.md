---
title: ReplaceRegex()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla matchningar av det reguljära uttrycket med den angivna strängen.
type: docs
weight: 495
url: /sv/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metod


Ersätter alla matchningar av det reguljära uttrycket med den angivna strängen.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Det reguljära uttrycket [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att hämta strängarna som ska ersättas. |
| newText | [System::String](../../../system/string/) | Strängen för att ersätta alla förekomster av de strängar som ska ersättas. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar



Följande kodexempel visar hur man ersätter text med reguljära uttryck med den angivna strängen. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [String](../../../system/string/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [IPresentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)