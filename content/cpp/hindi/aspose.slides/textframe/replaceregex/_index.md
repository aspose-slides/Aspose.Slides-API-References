---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API संदर्भ
description: नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है।
type: docs
weight: 183
url: /hi/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) विधि

नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है।

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | बदलने के लिए स्ट्रिंग्स प्राप्त करने हेतु नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| newText | [System::String](../../../system/string/) | बदलने के लिए स्ट्रिंग्स की सभी घटनाओं को बदलने वाली स्ट्रिंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | बदलाव ऑपरेशन परिणाम [IFindResultCallback](../../ifindresultcallback/) को सहेजने के लिए कॉलबैक ऑब्जेक्ट। |

## टिप्पणियाँ

निम्नलिखित नमूना कोड दर्शाता है कि निर्दिष्ट स्ट्रिंग के साथ नियमित अभिव्यक्ति का उपयोग करके टेक्स्ट को कैसे बदलें। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [String](../../../system/string/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [TextFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)