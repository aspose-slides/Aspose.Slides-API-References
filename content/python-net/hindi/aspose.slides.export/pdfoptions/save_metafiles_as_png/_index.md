---
title: save_metafiles_as_png property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png प्रॉपर्टी
प्रस्तुति में उपयोग किए गए सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True.
            पढ़ें/लिखें **bool**.

### टिप्पणी
डिफ़ॉल्ट **true** है।
            Pdf दस्तावेज़ में वेक्टर ग्राफ़िक्स और रास्टर छवियां हो सकती हैं। 
            यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत Metafile 
            छवि को Png फॉर्मेट में बदलकर Pdf में रास्टर के रूप में संग्रहीत किया जाता है। 
            यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत Metafile 
            को Pdf वेक्टर ग्राफ़िक्स में बदल दिया जाता है। प्रत्येक विधि के फायदे 
            और नुकसान हैं। उदाहरण के लिए, यदि Metafile को PNG में बदल दिया जाता है, 
            तो परिणामी दस्तावेज़ स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। 
            यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में बदल दिया जाता है, 
            तो Pdf व्यूइंग टूल में प्रदर्शन समस्याएं संभव हो सकती हैं।

### परिभाषा:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### देखें भी
* क्लास [`PdfOptions`](/slides/python-net/hi/aspose.slides.export/pdfoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)