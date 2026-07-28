---
title: ReplaceText()
second_title: Aspose.Slides C++ API-referencia
description: Az összes előforduló megadott szöveget egy másik megadott szövegre cseréli.
type: docs
weight: 144
url: /hu/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus

Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A helyettesítendő karakterlánc. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely lecseréli az oldText összes előfordulását. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../ifindresultcallback/). |

## Megjegyzések

Az alábbi példakód bemutatja, hogyan cserélhető egy megadott karakterlánc egy másik megadott karakterláncra.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Cserélje le az összes különálló 'the' előfordulást a '<em><strong>'-ra
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [ITextFrame](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)