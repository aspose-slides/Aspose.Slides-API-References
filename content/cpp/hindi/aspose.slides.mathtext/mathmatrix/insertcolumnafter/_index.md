---
title: InsertColumnAfter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट स्तम्भ के बाद एक नया स्तम्भ सम्मिलित करें। नई स्तम्भ में सभी तत्व प्रारंभ में null होते हैं।
type: docs
weight: 339
url: /hi/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) विधि

एक नया स्तम्भ निर्दिष्ट स्तम्भ के बाद सम्मिलित करें। नई स्तम्भ में सभी तत्व प्रारंभिक रूप से null होते हैं।

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | नए स्तम्भ को सम्मिलित करने के बाद वाले स्तम्भ का सूचकांक |
## टिप्पणी

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## देखें

* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)