---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: मैट्रिक्स का तत्व
type: docs
weight: 209
url: /hi/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) मेथड


मैट्रिक्स का तत्व

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | **int32_t** | row का शून्य-आधारित सूचकांक जिसे आइटम प्राप्त करने के लिए उपयोग किया जाता है |
| column | **int32_t** | column का शून्य-आधारित सूचकांक जिसे आइटम प्राप्त करने के लिए उपयोग किया जाता है |

### वापसी मान


## टिप्पणियाँ



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)