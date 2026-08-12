---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पैराग्राफ को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।
type: docs
weight: 105
url: /hi/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) विधि

निश्चित पैराग्राफ को HTML में परिवर्तित करता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | पहला पैराग्राफ इंडेक्स **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) गणना **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | परिवर्तन विकल्प [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### वापसी मान

उत्पन्न HTML।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* क्लास [IParagraphCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)