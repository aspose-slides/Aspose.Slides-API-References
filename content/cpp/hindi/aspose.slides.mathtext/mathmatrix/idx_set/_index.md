---
title: idx_set()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मैट्रिक्स का तत्व
type: docs
weight: 222
url: /hi/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) मेथड

मैट्रिक्स का तत्व

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | **int32_t** | आइटम प्राप्त करने के लिए पंक्ति का शून्य-आधारित सूचकांक |
| column | **int32_t** | आइटम प्राप्त करने के लिए स्तंभ का शून्य-आधारित सूचकांक |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* कक्षा [IMathElement](../../imathelement/)
* कक्षा [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)