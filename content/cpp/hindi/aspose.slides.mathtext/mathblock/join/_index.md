---
title: Join()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस गणितीय ब्लॉक के साथ एक गणितीय तत्व को जोड़ता है
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) विधि

इस गणितीय ब्लॉक के साथ एक गणितीय तत्व को जोड़ता है

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | जोड़ने के लिए तत्व |

### वापसी मान

[IMathBlock](../../imathblock/) का वर्तमान इंस्टेंस
## टिप्पणियां



उदाहरण: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) विधि

इस गणितीय ब्लॉक के साथ गणितीय पाठ को जोड़ता है

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | जोड़ने के लिए गणितीय पाठ |

### वापसी मान

एक नया [IMathBlock](../../imathblock/) जो इस इंस्टेंस और निर्दिष्ट तर्क को सम्मिलित करता है
## टिप्पणियां



उदाहरण: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)