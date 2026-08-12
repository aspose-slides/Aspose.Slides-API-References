---
title: ReplaceText()
second_title: Aspose.Slides C++ API रेफ़रेंस के लिए
description: निर्दिष्ट पाठ की सभी घटनाओं को अन्य निर्दिष्ट पाठ से बदलता है।
type: docs
weight: 170
url: /hi/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) विधि

निर्दिष्ट पाठ के सभी आवृत्तियों को दूसरे निर्दिष्ट पाठ से बदलता है।

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | बदलने के लिए स्ट्रिंग। |
| newText | [System::String](../../../system/string/) | सभी oldText आवृत्तियों को बदलने के लिए स्ट्रिंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | रिप्लेसमेंट ऑपरेशन परिणाम सहेजने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../ifindresultcallback/)। |

## टिप्पणियाँ

निम्नलिखित उदाहरण कोड दिखाता है कि एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से कैसे बदलें।
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग-अलग 'the' प्रविष्टियों को '<em><strong>' से बदलें
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)