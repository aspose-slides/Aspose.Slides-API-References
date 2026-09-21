---
title: formula property
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.animation/point/formula/
weight: 20
---
## फ़ॉर्मूला प्रॉपर्टी
मूल्यों, from, to, by एट्रिब्यूट्स के भीतर फ़ॉर्मूला इनका उपयोग करके बनाए जा सकते हैं:
            मानक अंकगणितीय ऑपरेटर: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            स्थिरांक: ‘pi’ ‘e’
            शर्तीय ऑपरेटर: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            तुलनात्मक ऑपरेटर: '==', '>=', '', '!=', '!'
            त्रिकोणमितीय ऑपरेटर: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            प्राकृतिक लघुगणक ‘ln()’
            प्रॉपर्टी संदर्भ (host supported properties)
            
            उदाहरण के लिए: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            पढ़ें/लिखें **str**.

### परिभाषा:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### देखें भी
* क्लास [`Point`](/slides/python-net/hi/aspose.slides.animation/point)
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)