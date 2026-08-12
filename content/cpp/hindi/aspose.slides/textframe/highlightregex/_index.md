---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाइलाइट करता है।
type: docs
weight: 157
url: /hi/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) विधि

नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | हाइलाइट करने के लिए पाठ प्राप्त करने हेतु नियमित अभिव्यक्ति का पाठ। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | हाइलाइटिंग विकल्प। |

## टिप्पणियाँ


अप्रचलित
:   उपयोग करें HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) विधि के बजाय। विधि को संस्करण 24.10 के रिलीज़ के बाद हटा दिया जाएगा।

निम्नलिखित कोड नमूना दिखाता है कि कैसे नियमित अभिव्यक्ति का उपयोग करके [TextFrame](../) में पाठ को हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 10 या अधिक अक्षर वाले सभी शब्दों को हाइलाइट कर रहा है
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) विधि

नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने हेतु नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |

## टिप्पणियाँ



निम्नलिखित कोड नमूना दिखाता है कि कैसे नियमित अभिव्यक्ति का उपयोग करके [TextFrame](../) में पाठ को हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 10 या अधिक अक्षर वाले सभी शब्दों को हाइलाइट कर रहा है
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [ITextHighlightingOptions](../../itexthighlightingoptions/)
* क्लास [TextFrame](../)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)