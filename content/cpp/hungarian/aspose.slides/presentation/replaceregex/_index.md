---
title: ReplaceRegex()
second_title: Aspose.Slides C++ API referencia
description: Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.
type: docs
weight: 534
url: /hu/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method


Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/), amely a helyettesítendő karakterláncokat adja. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely a helyettesítendő karakterláncok minden előfordulását lecseréli. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |
## Megjegyzés



Az alábbi kódrészlet bemutatja, hogyan lehet a szöveget reguláris kifejezéssel a megadott karakterláncra cserélni. 
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
* Osztály [Presentation](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)