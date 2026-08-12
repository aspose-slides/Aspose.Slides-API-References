---
title: ReplaceRegex()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है।
type: docs
weight: 157
url: /hi/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) विधि

नियमित अभिव्यक्ति के सभी मेलों को निर्दिष्ट स्ट्रिंग से बदलता है।

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | रेगुलर एक्सप्रेशन [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) को बदलने के लिए स्ट्रिंग प्राप्त करने हेतु। |
| newText | [System::String](../../../system/string/) | सभी बदलने वाली स्ट्रिंग्स के सभी घटनाओं को बदलने के लिए स्ट्रिंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |
## टिप्पणी

निम्नलिखित कोड उदाहरण दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके निर्दिष्ट स्ट्रिंग के साथ टेक्स्ट को कैसे बदलें। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [String](../../../system/string/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [ITextFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)