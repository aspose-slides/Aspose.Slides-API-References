---
title: Join()
second_title: Aspose.Slides for C++ API संदर्भ
description: गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) विधि

गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | जोड़ने के लिए तत्व |

### वापसी मान

एक नया [IMathBlock](../../imathblock/) जिसमें यह इंस्टेंस और निर्दिष्ट तर्क शामिल है
## टिप्पणी



उदाहरण: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) विधि

गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | जोड़ने के लिए गणितीय पाठ |

### वापसी मान

एक नया [IMathBlock](../../imathblock/) जिसमें यह इंस्टेंस और निर्दिष्ट तर्क शामिल है
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)