---
title: HighlightText()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla matchningar av provtexten med den angivna färgen.
type: docs
weight: 456
url: /sv/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) method

Markerar alla matchningar av provtexten med den angivna färgen.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texten som ska markeras. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen som ska användas för att markera texten. |
## Anmärkningar

Följande kodexempel visar hur man markerar text i en PowerPoint-presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// markerar alla enskilda 'the'-förekomster
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

Markerar alla matchningar av provtexten med den angivna färgen.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texten som ska markeras. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen som ska användas för att markera texten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsökalternativ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar

Följande kodexempel visar hur man markerar text i en PowerPoint-presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// markerar alla enskilda 'the'-förekomster
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Color](../../../system.drawing/color/)
* Klass [IPresentation](../)
* Klass [ITextSearchOptions](../../itextsearchoptions/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)