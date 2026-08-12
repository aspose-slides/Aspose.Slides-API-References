---
title: idx_get()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: मैट्रिक्स के तत्व
type: docs
weight: 209
url: /hi/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) विधि

मैट्रिक्स के तत्व

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | **int32_t** | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | **int32_t** | आइटम प्राप्त करने के लिए स्तंभ का शून्य-आधारित सूचकांक |

### रिटर्न मान


## टिप्पणियां



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)