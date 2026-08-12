---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित कॉलम से पहले एक नया कॉलम सम्मिलित करें। प्रारम्भ में नई कॉलम में सभी तत्व null होते हैं।
type: docs
weight: 326
url: /hi/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) विधि

निर्दिष्ट कॉलम से पहले एक नया कॉलम सम्मिलित करें। नई कॉलम में सभी तत्व प्रारंभ में null होते हैं।

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | एक नया कॉलम सम्मिलित करने से पहले कॉलम का इंडेक्स |

## टिप्पणी

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## संबंधित देखें

* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)