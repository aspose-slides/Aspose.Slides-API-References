---
title: get_PieSplitBy()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यह निर्धारित करने के लिए निर्दिष्ट करता है कि पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं। यह प्रॉपर्टी न केवल इस सीरीज़ की है बल्कि पैरेंट सीरीज़ समूह की सभी सीरीज़ की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए get_ParentSeriesGroup()->get(set)_PieSplitBy() पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य PieSplitType.
type: docs
weight: 755
url: /hi/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() मेथड

निर्दिष्ट करता है कि कौन से डेटा बिंदु दूसरे पाई या बार में पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट पर स्थित हैं, इसे कैसे निर्धारित किया जाए। यह प्रॉपर्टी न केवल इस सीरीज़ की है बल्कि पैरेंट सीरीज़ समूह की सभी सीरीज़ की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। ParentSeriesGroup प्रॉपर्टी का उपयोग करके पैरेंट सीरीज़ समूह तक पहुँचें। मान बदलने के लिए [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य [PieSplitType](../../piesplittype/)।

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## टिप्पणी

1) यह [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() प्रॉपर्टी का प्रोजेक्शन है। 2) यदि प्रॉपर्टी मान [PieSplitType::Custom](../../piesplittype/) है तो आप [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) प्रॉपर्टी के साथ कस्टम स्प्लिट जानकारी परिभाषित कर सकते हैं।

## संबंधित देखें

* एनम [PieSplitType](../../piesplittype/)
* क्लास [ChartSeries](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)