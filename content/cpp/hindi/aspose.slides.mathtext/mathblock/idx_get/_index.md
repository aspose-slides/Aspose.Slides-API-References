---
title: idx_get()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट अनुक्रमणिका पर IMathElement प्राप्त करता है।
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) विधि


निर्दिष्ट अनुक्रमणिका पर [IMathElement](../../imathelement/) प्राप्त करता है।

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | आइटम का शून्य-आधारित इंडेक्स |

### रिटर्न मान

गणितीय तत्व।

## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)