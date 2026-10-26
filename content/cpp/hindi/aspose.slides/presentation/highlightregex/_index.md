---
title: HighlightRegex()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: निर्दिष्ट रंग के साथ नियमित अभिव्यक्ति के सभी मिलानों को हाइलाइट करता है।
type: docs
weight: 508
url: /hi/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

नियमित अभिव्यक्ति के सभी मिलानों को निर्दिष्ट रंग के साथ हाइलाइट करता है।

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | हाइलाइट करने के लिए स्ट्रिंग्स प्राप्त करने हेतु रेग्यूलर एक्सप्रेशन [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | पाठ को हाइलाइट करने का रंग। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | सर्च परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |

## टिप्पणियाँ

निम्नलिखित कोड नमूना दिखाता है कि नियमित अभिव्यक्ति का उपयोग करके PowerPoint [Presentation](../) में पाठ को कैसे हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10 या अधिक अक्षरों वाले सभी शब्दों को हाइलाइट कर रहा है
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Regex](../../../system.text.regularexpressions/regex/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)