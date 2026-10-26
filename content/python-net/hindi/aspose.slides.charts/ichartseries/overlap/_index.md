---
title: overlap property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## ओवरलैप प्रॉपर्टी
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%).
 यह प्रॉपर्टी न केवल इस सीरीज़ की है बल्कि पैरेंट सीरीज़ समूह की सभी सीरीज़ की भी है।
 यह पैरेंट सीरीज़ समूह में उपयुक्त प्रॉपर्टी का प्रोजेक्शन है, और इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है।
 मूल्य बदलने के लिए, ParentSeriesGroup.Overlap पढ़ें/लिखें प्रॉपर्टी का उपयोग करें।
 केवल पढ़ने योग्य **int**।

### टिप्पणी

Overlap निर्दिष्ट करता है कि बार और कॉलम की ओवरलैप या स्पेसिंग उनकी चौड़ाई के प्रतिशत में कितना है:
- -100%: अधिकतम अंतर (बार पूरी तरह से अलग हैं)।
- 0%: बार साइड बाई साइड रखे जाते हैं बिना ओवरलैप या स्पेसिंग के।
- 100%: अधिकतम ओवरलैप (बार पूरी तरह से एक दूसरे पर ओवरलैप होते हैं)।
यह प्रॉपर्टी ParentSeriesGroup.Overlap का प्रोजेक्शन है।

### परिभाषा:
```python
@property
def overlap(self):
    ...
```

### देखें भी
* क्लास [`IChartSeries`](/slides/python-net/hi/aspose.slides.charts/ichartseries)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)