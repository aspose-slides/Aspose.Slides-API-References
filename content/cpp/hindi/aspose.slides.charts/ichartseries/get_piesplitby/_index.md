---
title: get_PieSplitBy()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि कैसे तय किया जाए कि कौन से डेटा बिंदु दूसरे पाई या बार में हैं, जब pie-of-pie या bar-of-pie चार्ट बनाते हैं। यह प्रॉपर्टी न केवल इस सीरीज की है बल्कि पैरेंट सीरीज ग्रुप की सभी सीरीज की भी है - यह उपयुक्त ग्रुप प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए get_ParentSeriesGroup()->get(set)_PieSplitBy() read/write प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य PieSplitType.
type: docs
weight: 729
url: /hi/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() विधि


निर्दिष्ट करता है कि किस प्रकार निर्धारित किया जाए कि कौन से डेटा बिंदु दूसरी पाई या बार में स्थित हैं, जब पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट बनाते हैं। यह प्रॉपर्टी न केवल इस श्रृंखला की है बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृंखलाओं की भी है - यह उपयुक्त ग्रुप प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() read/write प्रॉपर्टी का उपयोग करके मान बदलें। केवल-पढ़ने योग्य [PieSplitType](../../piesplittype/)।

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## टिप्पणी


1) यह प्रॉपर्टी [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() का प्रोजेक्शन है। 2) यदि प्रॉपर्टी मान [PieSplitType::Custom](../../piesplittype/) है तो आप [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) प्रॉपर्टी के साथ कस्टम स्प्लिट जानकारी परिभाषित कर सकते हैं। 
## देखें

* Enum [PieSplitType](../../piesplittype/)
* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)