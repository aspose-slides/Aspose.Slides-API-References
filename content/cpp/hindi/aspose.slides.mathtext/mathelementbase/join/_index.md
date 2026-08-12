---
title: Join()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) विधि

गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | जोड़ने के लिए तत्व |

### वापसी मान

एक नया [IMathBlock](../../imathblock/) जिसमें यह इंस्टेंस और निर्दिष्ट आर्ग्युमेंट शामिल है

## टिप्पणियाँ



उदाहरण: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) विधि

गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | जोड़ने के लिए गणितीय पाठ |

### वापसी मान

एक नया [IMathBlock](../../imathblock/) जिसमें यह इंस्टेंस और निर्दिष्ट आर्ग्युमेंट शामिल है

## टिप्पणियाँ



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)