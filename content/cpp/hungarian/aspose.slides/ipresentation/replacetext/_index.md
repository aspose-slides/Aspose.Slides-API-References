---
title: ReplaceText()
second_title: Aspose.Slides C++ API referenciája
description: Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.
type: docs
weight: 482
url: /hu/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metódus

Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A lecserélendő karakterlánc. |
| newText | [System::String](../../../system/string/) | A karakterlánc, amely minden oldText előfordulását lecseréli. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Szövegkeresési beállítások [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../ifindresultcallback/). |
## Megjegyzések

Az alábbi példakód bemutatja, hogyan cserélhetünk egy megadott karakterláncot egy másik megadott karakterláncra.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Cserélje le az összes különálló 'the' előfordulást a '<em><strong>' szöveggel
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ITextSearchOptions](../../itextsearchoptions/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [IPresentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)