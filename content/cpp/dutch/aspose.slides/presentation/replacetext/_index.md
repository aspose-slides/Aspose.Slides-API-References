---
title: ReplaceText()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle verschijningen van de opgegeven tekst door een andere opgegeven tekst.
type: docs
weight: 521
url: /nl/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Vervangt alle verschijningen van de opgegeven tekst door een andere opgegeven tekst.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | De tekenreeks die moet worden vervangen. |
| newText | [System::String](../../../system/string/) | De tekenreeks om alle verschijningen van oldText te vervangen. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende voorbeeldcode toont hoe je één opgegeven tekenreeks vervangt door een andere opgegeven tekenreeks. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Vervang alle afzonderlijke 'the'-verschijningen door '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)