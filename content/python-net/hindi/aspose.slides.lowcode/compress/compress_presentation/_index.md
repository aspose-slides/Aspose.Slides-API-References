---
title: compress_presentation method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
सभी उपलब्ध संपीड़न चरणों को लागू करके प्रस्तुति का आकार कम करता है:
            
* अपयोगी मास्टर स्लाइड्स को हटाता है **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* अपयोगी लेआउट स्लाइड्स को हटाता है **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* केवल एम्बेडेड फ़ॉन्ट्स में वास्तव में उपयोग किए गए ग्लिफ़ को रखता है **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* चित्र की रेज़ोल्यूशन को 150 DPI तक घटाता है और चित्रों के कटे हुए क्षेत्रों को हटाता है **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/hi/aspose.slides/presentation) | संपीड़न के लिए प्रस्तुति। |

### टिप्पणी

संपीड़न को अनुकूलित करने के लिए, उदाहरण के लिए अलग चित्र रेज़ोल्यूशन का उपयोग करने या किसी चरण को छोड़ने के लिए, ऊपर सूचीबद्ध विधियों को इस एक के बजाय व्यक्तिगत रूप से कॉल करें। चित्रों के कटे हुए क्षेत्रों को स्थायी रूप से हटा दिया जाता है और PowerPoint में उन्हें पुनर्स्थापित नहीं किया जा सकता।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` `None` है। |



### संबंधित देखें
* क्लास [`Compress`](/slides/python-net/hi/aspose.slides.lowcode/compress)
* क्लास [`Presentation`](/slides/python-net/hi/aspose.slides/presentation)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)