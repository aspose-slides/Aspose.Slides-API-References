---
title: ExportToHtml()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट पैराग्राफ़ को HTML में बदलता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।
type: docs
weight: 170
url: /hi/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) विधि

निर्दिष्ट पैराग्राफ़ को HTML में बदलता है और इसे String ऑब्जेक्ट के रूप में लौटाता है।

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | पहला पैराग्राफ इंडेक्स **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) गिनती **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | रूपांतरण विकल्प [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

## वापसी मान

जनित HTML।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Class [ParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)