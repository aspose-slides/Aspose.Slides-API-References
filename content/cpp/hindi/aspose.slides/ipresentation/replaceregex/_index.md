---
title: ReplaceRegex()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट स्ट्रिंग से बदलता है।
type: docs
weight: 495
url: /hi/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) मेथड

नियमित अभिव्यक्ति के सभी मिलान को निर्दिष्ट स्ट्रिंग से बदलता है।

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | बदलने के लिए स्ट्रिंग प्राप्त करने वाली नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| newText | [System::String](../../../system/string/) | बदलने योग्य स्ट्रिंग्स की सभी घटनाओं को बदलने के लिए स्ट्रिंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | [IFindResultCallback](../../ifindresultcallback/) खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |
## टिप्पणी

निम्नलिखित कोड नमूना दर्शाता है कि कैसे नियमित अभिव्यक्ति का उपयोग करके टेक्स्ट को निर्दिष्ट स्ट्रिंग से बदलें। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [String](../../../system/string/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [IPresentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)