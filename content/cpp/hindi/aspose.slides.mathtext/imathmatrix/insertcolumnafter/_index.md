---
title: InsertColumnAfter()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: निर्दिष्ट कॉलम के बाद एक नया कॉलम डालें। प्रारम्भ में नई कॉलम के सभी तत्व शून्य होते हैं।
type: docs
weight: 326
url: /hi/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) विधि

निर्दिष्ट कॉलम के बाद एक नया कॉलम डालें। प्रारम्भ में नई कॉलम के सभी तत्व शून्य होते हैं।

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | नए कॉलम को डालने के बाद वाले कॉलम का सूचकांक |

## टिप्पणियाँ

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## देखें

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)