---
title: get_ExplicitBreak()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: "Explicit break यह निर्दिष्ट करता है कि Box ऑब्जेक्ट की शुरुआत में एक लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत में घुमाव लेती है। यह गणितीय पाठ की पिछली पंक्ति पर ऑपरेटर की संख्या निर्धारित करता है जिसे वर्तमान गणितीय पाठ की पंक्ति के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (no explicit break)"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() मेथड

Explicit break यह निर्धारित करता है कि क्या Box ऑब्जेक्ट की शुरुआत में एक लाइन ब्रेक है, जिससे लाइन Box ऑब्जेक्ट की शुरुआत में घुमाव लेती है। यह पिछले गणितीय पाठ की लाइन पर ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान गणितीय पाठ की लाइन के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफॉल्ट: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## देखें

* क्लास [IMathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)