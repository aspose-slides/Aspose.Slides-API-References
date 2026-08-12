---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति में उपयोग की गई सभी मेटाफाइल्स को PNG छवियों में बदलने के लिए True है। पढ़ें bool.
type: docs
weight: 287
url: /hi/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() विधि


सभी प्रस्तुति में उपयोग की गई मेटाफाइल्स को PNG छवियों में बदलने के लिए True है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## टिप्पणी


डिफ़ॉल्ट **true** है। Pdf दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियां रख सकता है। यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत Metafile छवि को Png फ़ॉर्मेट में परिवर्तित किया जाता है और Pdf में रास्टर छवि के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है। प्रत्येक विधि के अपने फायदे और नुकसान हैं। उदाहरण के लिए, यदि Metafile को PNG में परिवर्तित किया जाता है, तो परिणामस्वरूप दस्तावेज़ के स्केलिंग के दौरान कुछ गुणवत्ता हानि हो सकती है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है, तो Pdf व्यूइंग टूल में प्रदर्शन संबंधी समस्याएं हो सकती हैं। 

## देखें

* क्लास [IPdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)