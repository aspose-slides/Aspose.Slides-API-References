---
title: ReplaceText()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.
type: docs
weight: 170
url: /nl/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | De te vervangen tekenreeks. |
| newText | [System::String](../../../system/string/) | De tekenreeks die alle voorkomens van oldText vervangt. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Tekstzoekopties [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-object voor het opslaan van het resultaat van de vervangingsoperatie [IFindResultCallback](../../ifindresultcallback/). |
## Opmerkingen



De volgende voorbeeldcode toont hoe één opgegeven tekenreeks te vervangen door een andere opgegeven tekenreeks. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Vervang alle afzonderlijke 'the' voorkomens door '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)