---
title: set_range method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
चार्ट डेटा रेंज सेट करें। नई डेटा रेंज के आधार पर सीरीज़ और श्रेणियां अपडेट की जाएंगी।
यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में सीरीज़ की गिनती से अधिक हो तो वर्तमान संग्रह की अंतिम सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ संग्रह के अंत में जोड़ी जाएगी।


```python
def set_range(self, formula):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| formula | **str** | सेल्स डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |


### अपवाद

| अपवाद | वर्णन |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula is None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula has incorrect format. |



### देखें
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)