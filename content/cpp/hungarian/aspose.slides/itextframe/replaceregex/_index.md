---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API Referenciája
description: A reguláris kifejezés összes egyezését a megadott karakterlánccal helyettesíti.
type: docs
weight: 157
url: /hu/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metódus


A reguláris kifejezés minden egyezését a megadott karakterlánccal helyettesíti.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) a helyettesítendő karakterláncok lekéréséhez. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely a helyettesítendő karakterláncok minden előfordulását lecseréli. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |
## Megjegyzések



Az alábbi kódrészlet bemutatja, hogyan lehet a reguláris kifejezést a megadott karakterlánc segítségével helyettesíteni. 
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
* Osztály [ITextFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)