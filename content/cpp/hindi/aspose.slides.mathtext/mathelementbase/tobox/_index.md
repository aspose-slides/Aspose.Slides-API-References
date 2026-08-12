---
title: ToBox()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड वस्तु (उदाहरण के लिए) ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित की जा सकती है कि भीतर लाइन ब्रेक की अनुमति न हो।
type: docs
weight: 261
url: /hi/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() विधि


इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड वस्तु (उदाहरण के लिए) ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित की जा सकती है कि भीतर लाइन ब्रेक की अनुमति न हो।

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### लौटाया गया मान

इस तत्व को अंदर रखे हुए तार्किक बॉक्स
## टिप्पणियाँ



उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBox](../../imathbox/)
* क्लास [MathElementBase](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्ररी [Aspose.Slides](../../../)