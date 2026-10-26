---
title: ReplaceRegex()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट स्ट्रिंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को प्रतिस्थापित करता है।
type: docs
weight: 534
url: /hi/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) मेथड

निर्दिष्ट स्ट्रिंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को प्रतिस्थापित करता है।

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) जिससे प्रतिस्थापित करने के लिये स्ट्रिंग्स प्राप्त होती हैं। |
| newText | [System::String](../../../system/string/) | सभी प्रतिस्थापित की जाने वाली स्ट्रिंग्स की घटनाओं को बदलने वाली स्ट्रिंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट। |
## टिप्पणी

निम्नलिखित कोड नमूना दिखाता है कि कैसे नियमित अभिव्यक्ति का उपयोग करके निर्दिष्ट स्ट्रिंग के साथ टेक्स्ट को प्रतिस्थापित किया जाता है। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [String](../../../system/string/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)