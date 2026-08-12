---
title: HighlightText()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट रंग के साथ नमूना टेक्स्ट की सभी मिलानों को हाइलाइट करता है।
type: docs
weight: 495
url: /hi/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) विधि

निर्दिष्ट रंग के साथ नमूना टेक्स्ट की सभी मिलानों को हाइलाइट करता है।

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | टेक्स्ट को हाइलाइट करने के लिए रंग। |
## टिप्पणियाँ

निम्नलिखित कोड नमूना दिखाता है कि PowerPoint प्रस्तुति में टेक्स्ट को कैसे हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// सभी अलग 'the' उपस्थिति को हाइलाइट करना
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) विधि

निर्दिष्ट रंग के साथ नमूना टेक्स्ट की सभी मिलानों को हाइलाइट करता है।

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | हाइलाइट करने के लिए टेक्स्ट। |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | टेक्स्ट को हाइलाइट करने के लिए रंग। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | टेक्स्ट खोज विकल्प [ITextSearchOptions](../../itextsearchoptions/)। |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | खोज परिणाम प्राप्त करने के लिए कॉलबैक ऑब्जेक्ट [IFindResultCallback](../../ifindresultcallback/)। |
## टिप्पणियाँ

निम्नलिखित कोड नमूना दिखाता है कि PowerPoint प्रस्तुति में टेक्स्ट को कैसे हाइलाइट किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// सभी अलग 'the' उपस्थिति को हाइलाइट करना
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Color](../../../system.drawing/color/)
* क्लास [Presentation](../)
* क्लास [ITextSearchOptions](../../itextsearchoptions/)
* क्लास [IFindResultCallback](../../ifindresultcallback/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)