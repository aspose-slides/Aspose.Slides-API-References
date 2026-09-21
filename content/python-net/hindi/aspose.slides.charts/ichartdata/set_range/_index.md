---
title: set_range method
second_title: Aspose.Slides के लिए Python .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
चार्ट डेटा रेंज सेट करें। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियों को अपडेट किया जाएगा।
यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में मौजूद सीरीज़ की संख्या से अधिक है, तो वर्तमान संग्रह में अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ को संग्रह के अंत में जोड़ दिया जाएगा।


```python
def set_range(self, formula):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| formula | **str** | सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None है। |
| **RuntimeError(Proxy error(ArgumentException))** | formula का प्रारूप गलत है। |



### संबंधित देखें
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)