---
title: ReplaceText()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट पाठ की सभी घटनाओं को दूसरे निर्दिष्ट पाठ से बदलता है।
type: docs
weight: 144
url: /hi/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) मेथड

निर्दिष्ट पाठ की सभी घटनाओं को अन्य निर्दिष्ट पाठ से बदलता है।

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | बदलने के लिए स्ट्रिंग। |
| newText | [System::String](../../../system/string/) | oldText की सभी घटनाओं को बदलने के लिए स्ट्रिंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | पाठ खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम [IFindResultCallback](../../ifindresultcallback/) प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट। |

## टिप्पणी

निम्नलिखित नमूना कोड दिखाता है कि कैसे एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से बदलें।

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग-अलग 'the' की घटनाओं को '<em><strong>' से बदलें
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ITextSearchOptions](../../itextsearchoptions/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [ITextFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)