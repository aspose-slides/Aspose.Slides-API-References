---
title: ReplaceRegex()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla matchningar av reguljärt uttryck med angiven sträng.
type: docs
weight: 183
url: /sv/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metod

Ersätter alla matchningar av reguljära uttrycket med angiven sträng.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Det reguljära uttrycket [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att få strängar som ska ersättas. |
| newText | [System::String](../../../system/string/) | Strängen för att ersätta alla förekomster av strängar som ska ersättas. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objekt för att spara ersättningsoperationens resultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar

Följande exempelprogram visar hur man ersätter text med reguljärt uttryck och angiven sträng. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [String](../../../system/string/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [TextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)