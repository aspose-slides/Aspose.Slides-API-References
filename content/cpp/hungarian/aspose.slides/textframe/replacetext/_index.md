---
title: ReplaceText()
second_title: Aspose.Slides C++ API referencia
description: Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.
type: docs
weight: 170
url: /hu/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus


Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A cserélendő karakterlánc. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely az oldText összes előfordulását lecseréli. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Visszahívási objektum a csere művelet eredményének mentéséhez [IFindResultCallback](../../ifindresultcallback/). |
## Megjegyzések



Az alábbi minta kód bemutatja, hogyan lehet egy megadott karakterláncot egy másik megadott karakterláncra cserélni. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Cserélje le az összes különálló 'the' előfordulást a '<em><strong>' elemre
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [TextFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)