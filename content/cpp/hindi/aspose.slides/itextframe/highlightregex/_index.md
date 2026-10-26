---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाइलाइट करता है।
type: docs
weight: 131
url: /hi/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) विधि


निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | हाइलाइट करने के लिए स्ट्रिंग प्राप्त करने हेतु नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने का रंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |
## टिप्पणियाँ



निम्नलिखित कोड उदाहरण दर्शाता है कि नियमित अभिव्यक्ति का उपयोग करके [TextFrame](../../textframe/) में पाठ को कैसे हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) विधि


निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | हाइलाइट करने के लिए पाठ प्राप्त करने हेतु नियमित अभिव्यक्ति का पाठ। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने का रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | हाइलाइटिंग विकल्प। |

डिप्रिकेटेड
:   इसके बजाय HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) विधि का उपयोग करें। विधि संस्करण 24.10 के रिलीज़ के बाद हटा दी जाएगी।

## साथ ही देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [ITextFrame](../)
* क्लास [String](../../../system/string/)
* क्लास [ITextHighlightingOptions](../../itexthighlightingoptions/)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)