---
title: ReplaceText()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla förekomster av den angivna texten med en annan angiven text.
type: docs
weight: 482
url: /sv/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

Ersätter alla förekomster av den angivna texten med en annan angiven text.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Strängen som ska ersättas. |
| newText | [System::String](../../../system/string/) | Strängen som ersätter alla förekomster av oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Alternativ för textsökning [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |

## Anmärkningar

Följande exempelprogram visar hur man ersätter en angiven sträng med en annan angiven sträng. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Ersätt alla separata 'the'-förekomster med '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ITextSearchOptions](../../itextsearchoptions/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [IPresentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)