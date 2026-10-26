---
title: ToBox()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस तत्व को एक गैर-दृश्‍य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या गणितीय पाठ के अन्य उदाहरण के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के तौर पर) संरेखण बिंदु के साथ या बिना ऑपरेटर एम्युलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो।
type: docs
weight: 274
url: /hi/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() विधि

यह तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या गणितीय पाठ के अन्य उदाहरण के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है, चाहे उसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो।

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### रिटर्न वैल्यू

Logical box with this element placed inside

## टिप्पणियाँ



उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBox](../../imathbox/)
* क्लास [IMathElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)