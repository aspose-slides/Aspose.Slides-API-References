---
title: ReplaceText()
second_title: Aspose.Slides för C++ API-referens
description: Ersätter alla förekomster av den angivna texten med en annan angiven text.
type: docs
weight: 170
url: /sv/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod


Ersätter alla förekomster av den angivna texten med en annan angiven text.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Strängen som ska ersättas. |
| newText | [System::String](../../../system/string/) | Strängen som ersätter alla förekomster av oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsökalternativ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Återuppringningsobjekt för att spara ersättningsoperationens resultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar



Följande exempelkod visar hur man ersätter en specificerad sträng med en annan specificerad sträng. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Ersätt alla separata 'the'-förekomster med '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)