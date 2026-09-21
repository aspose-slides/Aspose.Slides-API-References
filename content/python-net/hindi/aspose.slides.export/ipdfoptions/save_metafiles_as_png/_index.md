---
title: save_metafiles_as_png property
second_title: Aspose.Slides के लिए Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png गुण
True को सभी प्रस्तुति में प्रयुक्त metafiles को PNG छवियों में बदलने के लिए सेट किया जाता है।
            पढ़ें/लिखें **bool**.

### टिप्पणी

डिफ़ॉल्ट **true** है।
            Pdf दस्तावेज़ वेक्टर ग्राफ़िक्स और रास्टर छवियों को शामिल कर सकता है।
            यदि SaveMetafilesAsPng को true पर सेट किया जाता है तो स्रोत Metafile छवि Png प्रारूप में बदल दी जाती है और Pdf को रास्टर छवि के रूप में सहेजा जाता है। यदि SaveMetafilesAsPng को false पर सेट किया जाता है तो स्रोत Metafile Pdf वेक्टर ग्राफ़िक्स में बदल दिया जाता है। प्रत्येक दृष्टिकोण के फायदे और नुकसान होते हैं। उदाहरण के लिए, यदि Metafile को PNG में परिवर्तित किया जाता है, तो परिणामस्वरूप दस्तावेज़ के स्केलिंग के दौरान कुछ गुणवत्ता हानि संभव है। यदि Metafile को Pdf वेक्टर ग्राफ़िक्स में परिवर्तित किया जाता है, तो Pdf व्यूइंग टूल में प्रदर्शन समस्याएँ संभव हैं।

### परिभाषा:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### संबंधित देखें
* क्लास [`IPdfOptions`](/slides/python-net/hi/aspose.slides.export/ipdfoptions)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)