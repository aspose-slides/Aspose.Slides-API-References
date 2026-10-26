---
title: SetColumnsAlignment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करें
type: docs
weight: 274
url: /hi/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) विधि

निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करें

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | संरेखण सेट करने के लिए पहले स्तंभ का शून्य-आधारित सूचकांक |
| columnsCount | **uint32_t** | संरेखण निर्दिष्ट करने के लिये स्तंभों की संख्या |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | निर्धारित स्तंभ की नई क्षैतिज संरेखण मान |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## संबंधित देखें

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)