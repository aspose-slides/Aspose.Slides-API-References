---
title: get_HideDegree()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब Hide degree सत्य हो, डिग्री प्रदर्शित नहीं की जाएगी, जैसा कि \\u221A\\uD835\\uDC65 में है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathradical/get_hidedegree/
---
## IMMathRadical::get_HideDegree() विधि


जब Hide degree सत्य हो, डिग्री प्रदर्शित नहीं की जाएगी, जैसा कि \\u221A\\uD835\\uDC65 में है।

```cpp
virtual bool Aspose::Slides::MathText::IMathRadical::get_HideDegree()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // घन मूल
radical->set_HideDegree(true);
```

## देखें

* क्लास [IMathRadical](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)