---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पंक्ति से पहले नई पंक्ति डालें। प्रारम्भ में नई पंक्ति के सभी तत्व null होते हैं।
type: docs
weight: 287
url: /hi/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) विधि

निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें। प्रारम्भ में नई पंक्ति के सभी तत्व null होते हैं।

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | **int32_t** | नई पंक्ति डालने से पहले वाली पंक्ति का सूचकांक |
## टिप्पणियाँ



उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## देखें

* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)