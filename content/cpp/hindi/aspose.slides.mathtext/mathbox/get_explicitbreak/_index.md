---
title: get_ExplicitBreak()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत में मोड़ती है। यह गणितीय पाठ की पिछली पंक्ति में ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान पंक्ति के गणितीय पाठ के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई explicit break नहीं)"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() विधि


Explicit break यह निर्धारित करता है कि Box object की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन Box object की शुरुआत में मोड़ती है। यह गणितीय पाठ की पिछली पंक्ति में ऑपरेटर की संख्या निर्धारित करता है जिसे वर्तमान पंक्ति के गणितीय पाठ के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई explicit break नहीं)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## टिप्पणियां


उदाहरण:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## संबंधित देखें

* क्लास [MathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)