---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऑपरेटर एम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एक ही ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की गुणों को विरासत में लेती है। इसका मतलब है, उदाहरण के लिए, कि यह वर्ण लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर एम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() मेथड

ऑपरेटर एम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एक ही ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की गुणधर्मों को विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि यह वर्ण लाइन ब्रेक के बिंदु के रूप में उपयोग किया जा सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर एम्यूलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक ग्लिफ़ एक ऑपरेटर बनाने के लिए संयोजित होते हैं, जैसे '=='। डिफ़ॉल्ट मान: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## देखें

* क्लास [MathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)