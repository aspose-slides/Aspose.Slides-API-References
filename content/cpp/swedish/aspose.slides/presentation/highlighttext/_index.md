---
title: HighlightText()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla förekomster av exempeltexten med den angivna färgen.
type: docs
weight: 495
url: /sv/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metod

Markerar alla förekomster av exempeltexten med den angivna färgen.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texten att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
## Anmärkningar



Följande kodexempel visar hur man markerar text i en PowerPoint-presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// markerar alla separata 'the'-förekomster
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod

Markerar alla förekomster av exempeltexten med den angivna färgen.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texten att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Text-sökalternativ [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |
## Anmärkningar



Följande kodexempel visar hur man markerar text i en PowerPoint-presentation. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// markerar alla separata 'the'-förekomster
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Color](../../../system.drawing/color/)
* Klass [Presentation](../)
* Klass [ITextSearchOptions](../../itextsearchoptions/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)