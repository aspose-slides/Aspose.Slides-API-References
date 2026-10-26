---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides C++ API संदर्भ
description: प्रेज़ेंटेशन में उपयोग किए गए सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True सेट करें। पढ़ें bool.
type: docs
weight: 326
url: /hi/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() मेथड

True को सेट करके प्रेज़ेंटेशन में उपयोग किए गए सभी मेटाफाइलों को PNG छवियों में परिवर्तित किया जाता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## टिप्पणियाँ

डिफ़ॉल्ट **true** है। Pdf दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर इमेजेज़ दोनों रख सकता है। यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत Metafile छवि को Png फ़ॉर्मेट में परिवर्तित किया जाता है और Pdf में रास्टर इमेज के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है। प्रत्येक दृष्टिकोण के अपने फायदे और नुकसान हैं। उदाहरण के लिए, यदि Metafile को PNG में परिवर्तित किया जाता है, तो परिणामी दस्तावेज़ स्केलेशन के दौरान कुछ गुणवत्ता हानि हो सकती है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है, तो Pdf व्यूइंग टूल में प्रदर्शन संबंधी समस्याएँ हो सकती हैं।

## संबंधित देखें

* क्लास [PdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)