---
title: ReplaceText()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.
type: docs
weight: 482
url: /nl/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) methode


Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | De te vervangen tekenreeks. |
| newText | [System::String](../../../system/string/) | De tekenreeks waarmee alle voorkomens van oldText worden vervangen. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende voorbeeldcode laat zien hoe een opgegeven tekenreeks te vervangen door een andere opgegeven tekenreeks. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Vervang alle afzonderlijke 'the' voorkomens door '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [IPresentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)