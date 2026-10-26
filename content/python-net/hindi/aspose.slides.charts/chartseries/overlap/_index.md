---
title: overlap property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap प्रॉपर्टी
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            यह प्रॉपर्टी न केवल इस सीरीज़ की है बल्कि पैरेंट सीरीज़ समूह की सभी सीरीज़ की भी है। 
            यह पैरेंट सीरीज़ समूह में उपयुक्त प्रॉपर्टी का प्रोजेक्शन है, इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है।
            मान बदलने के लिए, **ParentSeriesGroup.Overlap** पढ़ने/लिखने वाली प्रॉपर्टी का उपयोग करें।
            केवल-पढ़ने योग्य **int**।

### टिप्पणियाँ
Overlap निर्दिष्ट करता है कि बार और कॉलम के बीच ओवरलैप या अंतराल की डिग्री उनके चौड़ाई के प्रतिशत के रूप में है:
            - -100%: अधिकतम अंतर (बार पूरी तरह अलग हैं)।
            - 0%: बार बिना ओवरलैप या अंतराल के बगल-बगल रखे होते हैं।
            - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप होते हैं)।
            यह प्रॉपर्टी **ParentSeriesGroup.Overlap** का प्रोजेक्शन है।

### परिभाषा:
```python
@property
def overlap(self):
    ...
```

### संबंधित देखें
* क्लास [`ChartSeries`](/slides/python-net/hi/aspose.slides.charts/chartseries)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)