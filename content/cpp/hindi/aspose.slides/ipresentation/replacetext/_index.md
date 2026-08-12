---
title: ReplaceText()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट पाठ की सभी घटनाओं को किसी अन्य निर्दिष्ट पाठ से बदलता है।
type: docs
weight: 482
url: /hi/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) विधि

निर्दिष्ट पाठ की सभी घटनाओं को किसी अन्य निर्दिष्ट पाठ से बदलता है।

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | बदलने के लिए स्ट्रिंग। |
| newText | [System::String](../../../system/string/) | oldText की सभी घटनाओं को बदलने वाली स्ट्रिंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../ifindresultcallback/)। |

## टिप्पणियाँ

निम्नलिखित नमूना कोड दर्शाता है कि कैसे एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से बदला जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग-अलग 'the' घटनाओं को '<em><strong>' से बदलें
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ITextSearchOptions](../../itextsearchoptions/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [IPresentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)