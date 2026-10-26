---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API संदर्भ
description: Markdown निर्यात के दौरान प्रत्येक non-SVG छवि (bitmap या metafile) के लिए कॉल किया जाता है। निर्दिष्ट लिंक का उपयोग करने के लिए true लौटाएँ, या डिफ़ॉल्ट सहेजने की लॉजिक लागू करने के लिए false लौटाएँ।
type: docs
weight: 300
url: /hi/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Markdown निर्यात के दौरान प्रत्येक non-SVG छवि (bitmap या metafile) के लिए कॉल किया जाता है। 

निर्दिष्ट *लिंक* का उपयोग करने के लिए **true** लौटाएँ, 

या डिफ़ॉल्ट सहेजने की लॉजिक लागू करने के लिए **false** लौटाएँ।

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## देखें

* क्लास [MarkdownSaveOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)