---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API Referenciája
description: Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.
type: docs
weight: 495
url: /hu/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) a cserélendő karakterláncok megszerzéséhez. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely a cserélendő összes előfordulást helyettesíti. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |

## Megjegyzés

A következő kódrészlet bemutatja, hogyan cserélhetünk szöveget reguláris kifejezéssel a megadott karakterláncra. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Regex](../../../system.text.regularexpressions/regex/)
* Osztály [String](../../../system/string/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [IPresentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)