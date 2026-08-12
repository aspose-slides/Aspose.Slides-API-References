---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जो दिए गए टेक्स्ट को शामिल करते हैं।
type: docs
weight: 66
url: /hi/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) विधि

निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जो दिए गए टेक्स्ट को शामिल करते हैं।

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | खोज करने के लिए स्लाइड। |
| text | [System::String](../../../system/string/) | टेक्स्ट फ्रेम के भीतर खोजे जाने वाला टेक्स्ट। |
| checkPlaceholderText | **bool** | यह दर्शाता है कि क्या खाली टेक्स्ट फ्रेम को शामिल किया जाए, लेकिन जिनका प्लेसहोल्डर टेक्स्ट खोज टेक्स्ट को शामिल करता है। |

### रिटर्न मान

एक एरे जिसमें [ITextFrame](../../../aspose.slides/itextframe/) ऑब्जेक्ट्स हैं जो निर्दिष्ट टेक्स्ट को शामिल करते हैं।

## देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ITextFrame](../../../aspose.slides/itextframe/)
* क्लास [IBaseSlide](../../../aspose.slides/ibaseslide/)
* क्लास [String](../../../system/string/)
* क्लास [SlideUtil](../)
* नेमस्पेस [Aspose::Slides::Util](../../)
* लाइब्रेरी [Aspose.Slides](../../../)