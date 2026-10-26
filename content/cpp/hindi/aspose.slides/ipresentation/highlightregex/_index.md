---
title: HighlightRegex()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलान को हाइलाइट करता है।
type: docs
weight: 469
url: /hi/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) मेथड


निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति की सभी मेलों को हाइलाइट करता है।

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | हाइलाइट करने के लिए स्ट्रिंग प्राप्त करने हेतु नियमित अभिव्यक्ति [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने के लिए रंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |
## टिप्पणी



निम्नलिखित कोड उदाहरण दर्शाता है कि नियमित अभिव्यक्ति का उपयोग करके PowerPoint [Presentation](../../presentation/) में पाठ को कैसे हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [IPresentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)