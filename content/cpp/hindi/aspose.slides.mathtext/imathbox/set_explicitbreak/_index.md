---
title: set_ExplicitBreak()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत में ही रैप हो जाती है। यह गणितीय पाठ की पिछली पंक्ति में ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान पंक्ति के गणितीय पाठ के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) विधि


Explicit break निर्धारित करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत में ही रैप हो जाती है। यह गणितीय पाठ की पिछली पंक्ति में ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान पंक्ति के गणितीय पाठ के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## संबंधित देखें

* क्लास [IMathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)