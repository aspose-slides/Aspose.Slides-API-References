---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API संदर्भ
description: True को प्रस्तुति में उपयोग किए गए सभी मेटाफ़ाइल्स को PNG छवियों में बदलने के लिए उपयोग किया जाता है। **bool** लिखें।
type: docs
weight: 339
url: /hi/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) विधि

True को प्रस्तुति में उपयोग किए गए सभी मेटाफ़ाइल्स को PNG छवियों में परिवर्तित करने के लिए प्रयोग किया जाता है। लिखें **bool**।

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## टिप्पणियाँ

Default **true** है। Pdf दस्तावेज़ में वेक्टर ग्राफ़िक्स और रास्टर छवियाँ हो सकती हैं। यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत Metafile छवि को Png फ़ॉर्मेट में बदल दिया जाता है और Pdf में रास्टर छवि के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है। प्रत्येक दृष्टिकोण के फायदे और नुकसान हैं। उदाहरण के लिए, यदि Metafile को PNG में बदल दिया जाता है, तो परिणामस्वरूप दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में बदल दिया जाता है, तो Pdf व्यूइंग टूल में प्रदर्शन संबंधी समस्याएँ संभव हैं। 

## देखें

* क्लास [PdfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)