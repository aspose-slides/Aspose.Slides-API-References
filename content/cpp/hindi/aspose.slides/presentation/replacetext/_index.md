---
title: ReplaceText()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पाठ की सभी घटनाओं को अन्य निर्दिष्ट पाठ से बदलता है।
type: docs
weight: 521
url: /hi/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) मेथड


निर्दिष्ट पाठ की सभी घटनाओं को अन्य निर्दिष्ट पाठ से बदलता है।

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | बदलने के लिये स्ट्रिंग। |
| newText | [System::String](../../../system/string/) | सभी oldText की घटनाओं को बदलने के लिये स्ट्रिंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | पाठ खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम प्राप्त करने के लिये कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../ifindresultcallback/)। |
## टिप्पणियाँ



निम्नलिखित नमूना कोड दिखाता है कि कैसे एक निर्दिष्ट स्ट्रिंग को दूसरी निर्दिष्ट स्ट्रिंग से बदला जाता है। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग 'the' उपस्थितियों को '<em><strong>' से बदलें
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ITextSearchOptions](../../itextsearchoptions/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)