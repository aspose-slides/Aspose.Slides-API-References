---
title: formula property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.animation/ipoint/formula/
weight: 10
---
## फ़ॉर्मूला प्रॉपर्टी
Formulas within values, from, to, by attributes can be made up of these:
            मानक अंकगणितीय ऑपरेटर: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            स्थिरांक: ‘pi’ ‘e’
            शर्तीय ऑपरेटर: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            तुलना ऑपरेटर: '==', '>=', '', '!=', '!'
            त्रिकोणमितीय ऑपरेटर: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            प्राकृतिक लघुगणक ‘ln()’
            प्रॉपर्टी रेफ़रेन्स (होस्ट समर्थित प्रॉपर्टी)
            
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
* क्लास [`IPoint`](/slides/python-net/hi/aspose.slides.animation/ipoint)
* मॉड्यूल [`aspose.slides.animation`](/slides/python-net/hi/aspose.slides.animation)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)