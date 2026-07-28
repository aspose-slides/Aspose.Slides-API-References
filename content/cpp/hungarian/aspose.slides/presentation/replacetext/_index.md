---
title: ReplaceText()
second_title: Aspose.Slides C++ API Referencia
description: Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.
type: docs
weight: 521
url: /hu/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus

A megadott szöveg minden előfordulását egy másik megadott szövegre cseréli.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A helyettesítendő karakterlánc. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amellyel az oldText összes előfordulását helyettesítjük. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../ifindresultcallback/). |

## Megjegyzések

A következő példakód bemutatja, hogyan lehet egy megadott karakterláncot egy másik megadott karakterláncra cserélni.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Cserélje le az összes különálló 'the' előfordulást a '<em><strong>'-re
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [Presentation](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)