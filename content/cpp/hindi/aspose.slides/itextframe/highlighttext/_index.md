---
title: HighlightText()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट रंग के साथ नमूना पाठ के सभी मिलान को हाइलाइट करता है।
type: docs
weight: 105
url: /hi/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) method

नमूना टेक्स्ट के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिये टेक्स्ट। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | टेक्स्ट को हाइलाइट करने के लिये रंग। |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

नमूना टेक्स्ट के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिये टेक्स्ट। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | टेक्स्ट को हाइलाइट करने के लिये रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | हाइलाइटिंग विकल्प। |

अप्रचलित  
:   इसके बजाय HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) मेथड का उपयोग करें। यह मेथड संस्करण 24.10 के रिलीज़ के बाद हटा दिया जाएगा।

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

नमूना टेक्स्ट के सभी मिलान को निर्दिष्ट रंग से हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिये टेक्स्ट। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | टेक्स्ट को हाइलाइट करने के लिये रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | टेक्स्ट सर्च विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिये कॉलबैक वस्तु। |

## टिप्पणियाँ

निम्नलिखित कोड उदाहरण दर्शाता है कि कैसे [TextFrame](../../textframe/) में टेक्स्ट को हाइलाइट किया जाए।  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [ITextFrame](../)
* क्लास [ITextHighlightingOptions](../../itexthighlightingoptions/)
* क्लास [ITextSearchOptions](../../itextsearchoptions/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)