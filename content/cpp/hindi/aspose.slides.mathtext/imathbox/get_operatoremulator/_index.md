---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऑपरेटर एमुलेटर। जब true हो, बॉक्स और उसकी सामग्री एक एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की विशेषताओं को विरासत में प्राप्त करती है। इसका मतलब है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। ऑपरेटर एमुलेटर अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() मेथड

Operator Emulator. जब true हो, बॉक्स और उसकी सामग्री एक एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की विशेषताएँ विरासत में मिलती हैं। इसका मतलब है, उदाहरण के लिए, कि अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटर्स के साथ संरेखित किया जा सकता है। Operator Emulators अक्सर तब उपयोग किए जाते हैं जब एक या अधिक glyphs मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## देखें

* क्लास [IMathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)