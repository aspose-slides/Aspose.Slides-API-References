---
title: HighlightText()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलानों को हाइलाइट करता है।
type: docs
weight: 131
url: /hi/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) मेथड

निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिए पाठ नमूना। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) मेथड

निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिए पाठ। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | हाइलाइटिंग विकल्प। |

## टिप्पणी

अवमानित
:   इसके बजाय HighlightText(string text, Color highlightColor, ITextSearchOptions options) मेथड का उपयोग करें। यह मेथड संस्करण 24.10 के रिलीज़ के बाद हटा दिया जाएगा।

निम्नलिखित उदाहरण कोड दिखाता है कि कैसे [TextFrame](../) में टेक्स्ट को हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) मेथड

निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिए पाठ। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | पाठ खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../ifindresultcallback/)। |

## टिप्पणी

निम्नलिखित कोड उदाहरण दिखाता है कि कैसे [TextFrame](../) में टेक्स्ट को हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// सभी शब्द 'important' को हाइलाइट किया जा रहा है
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग-अलग 'the' उपस्थितियों को हाइलाइट किया जा रहा है
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [TextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)