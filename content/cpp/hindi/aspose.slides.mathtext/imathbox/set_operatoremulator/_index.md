---
title: set_OperatorEmulator()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "ऑपरेटर इम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की विशेषताओं को विरासत में लेती है। इसका मतलब है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक के बिंदु के रूप में काम कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) विधि

ऑपरेटर इम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की विशेषताएँ विरासत में लेती है। इसका अर्थ है, उदाहरण स्वरूप, कि यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे ‘==’। डिफ़ॉल्ट मान: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## संबंधित

* क्लास [IMathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)