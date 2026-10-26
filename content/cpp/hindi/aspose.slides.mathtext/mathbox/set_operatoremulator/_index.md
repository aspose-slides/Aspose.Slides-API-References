---
title: set_OperatorEmulator()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "ऑपरेटर इम्यूलेटर। जब सत्य हो, तो बॉक्स और उसकी सामग्री एकल ऑपरेटर के रूप में व्यवहार करती हैं और एक ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है, उदाहरण के लिए, कि यह वर्ण लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर्स अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़्स मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) विधि

ऑपरेटर इम्यूलेटर। जब सत्य हो, तो बॉक्स और उसकी सामग्री एकल ऑपरेटर के रूप में व्यवहार करती हैं और एक ऑपरेटर की विशेषताओं को विरासत में लेती हैं। इसका अर्थ है, उदाहरण के लिए, कि यह वर्ण लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर इम्यूलेटर्स अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़्स मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## टिप्पणियाँ

Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## संबंधित देखें

* क्लास [MathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)