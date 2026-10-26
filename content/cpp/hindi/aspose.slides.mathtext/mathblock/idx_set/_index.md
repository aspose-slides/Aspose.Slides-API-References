---
title: idx_set()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित अनुक्रमणिका पर IMathElement सेट करता है। 
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) method

निर्दिष्ट अनुक्रमणिका पर [IMathElement](../../imathelement/) को सेट करता है।

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | आइटम का शून्य-आधारित अनुक्रमणिका |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | गणितीय तत्व। |
## टिप्पणी

उदाहरण:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)