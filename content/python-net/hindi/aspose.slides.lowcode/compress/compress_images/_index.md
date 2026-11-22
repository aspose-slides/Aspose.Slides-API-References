---
title: compress_images method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
प्रेज़ेंटेशन में चित्रों का रिज़ॉल्यूशन घटाता है और उनके क्रॉप किए गए क्षेत्रों को हटा देता है,
            PowerPoint के "Compress Pictures" के समान, सभी चित्रों पर लागू होता है।
            स्लाइड, लेआउट स्लाइड और मास्टर स्लाइड पर मौजूद चित्रों को प्रोसेस किया जाता है, जिसमें ग्रुप शैप के अंदर के चित्र और शैप की पिक्चर फ़िल्स शामिल हैं।


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) | प्रोसेस करने के लिए प्रेज़ेंटेशन। |
| resolution | [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression) | प्रत्येक चित्र के प्रदर्शित आकार के सापेक्ष लक्ष्य रिज़ॉल्यूशन।<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/hi/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) चित्रों को अपरिवर्तित रखता है। |

### टिप्पणियाँ

लक्ष्य रिज़ॉल्यूशन पर या उससे नीचे वाले चित्र अपरिवर्तित छोड़ दिए जाते हैं; चित्रों को कभी अपस्केल नहीं किया जाता।


प्रसंस्करण नहीं किया गया: स्लाइड बैकग्राउंड, टेबल सेल फ़िल्स, चार्ट, SmartArt, GIF छवियाँ (ऐनिमेशन को संरक्षित रखने के लिए),
            SVG और मेटा फ़ाइल (EMF/WMF) चित्र।


क्रॉप किए गए क्षेत्रों को स्थायी रूप से हटा दिया जाता है और उन्हें PowerPoint में पुनः प्राप्त नहीं किया जा सकता।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` `None` है। |



### संबंधित देखें
* क्लास [`Compress`](/slides/python-net/hi/aspose.slides.lowcode/compress)
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* एन्यूमरेशन [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression)
* मॉड्यूल [`aspose.slides.lowcode`](/slides/python-net/hi/aspose.slides.lowcode)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)