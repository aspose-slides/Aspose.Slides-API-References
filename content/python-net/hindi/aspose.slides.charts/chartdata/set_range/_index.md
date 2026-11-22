---
title: set_range method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
चार्ट डेटा रेंज सेट करें। सीरीज़ और श्रेणियाँ नई डेटा रेंज के आधार पर अपडेट हो जाएँगी।  
यदि डेटा रेंज में सीरीज़ की संख्या चार्ट डेटा में सीरीज़ की गिनती से अधिक है, तो वर्तमान संग्रह में आखिरी सीरीज़ के समान प्रकार की अतिरिक्त सीरीज़ संग्रह के अंत में जोड़ी जाएगी।

```python
def set_range(self, formula):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| formula | **str** | कोशिकाओं के डेटा रेंज फ़ॉर्मूला। उदाहरण: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None है। |
| **RuntimeError(Proxy error(InvalidOperationException))** | असमर्थित चार्ट प्रकार |
| **RuntimeError(Proxy error(ArgumentException))** | formula का फ़ॉर्मेट गलत है। |

### देखें भी
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)