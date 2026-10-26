---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करें
type: docs
weight: 261
url: /hi/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) विधि


निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करें

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | संरेखण सेट करने के लिए पहले स्तंभ का शून्य-आधारित सूचकांक |
| columnsCount | **uint32_t** | संरेखण निर्दिष्ट करने के लिए स्तंभों की संख्या |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | निर्दिष्ट स्तंभ की नई क्षैतिज संरेखण मान |
## टिप्पणी



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## देखें

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* वर्ग [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)