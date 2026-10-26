---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API Referencia
description: Az összes reguláris kifejezés találatát a megadott karakterlánccal helyettesíti.
type: docs
weight: 183
url: /hu/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metódus


Az összes reguláris kifejezés találatát a megadott karakterlánccal helyettesíti.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) reguláris kifejezés a helyettesítendő karakterláncok lekéréséhez. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely a helyettesítendő karakterláncok összes előfordulását helyettesíti. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Visszahívási objektum a helyettesítési művelet eredményének [IFindResultCallback](../../ifindresultcallback/) mentéséhez. |
## Megjegyzés



Az alábbi példa kód bemutatja, hogyan lehet szöveget helyettesíteni reguláris kifejezéssel és megadott karakterlánccal. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Regex](../../../system.text.regularexpressions/regex/)
* Osztály [String](../../../system/string/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [TextFrame](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)