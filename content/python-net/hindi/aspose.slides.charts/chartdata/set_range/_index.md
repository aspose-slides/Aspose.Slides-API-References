---
title: set_range method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
चार्ट डेटा रेंज सेट करें। नई डेटा रेंज के आधार पर श्रृंखला और श्रेणियों को अपडेट किया जाएगा।
            यदि डेटा रेंज में श्रृंखलाओं की संख्या चार्ट डेटा में श्रृंखलाओं की गिनती से अधिक है, तो वर्तमान संग्रह में अंतिम श्रृंखला के समान प्रकार की अतिरिक्त श्रृंखलाएँ संग्रह के अंत में जोड़ी जाएँगी।

```python
def set_range(self, formula):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| formula | **str** | सेलों का डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | असमर्थित चार्ट प्रकार |
| **RuntimeError(Proxy error(ArgumentException))** | formula का स्वरूप गलत है। |

### देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)