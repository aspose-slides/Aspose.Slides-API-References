---
title: SetColumnAlignment()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट स्तंभ की क्षैतिज संरेखण सेट करता है
type: docs
weight: 261
url: /hi/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) विधि

निर्दिष्ट स्तंभ की क्षैतिज संरेखण सेट करता है

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | शून्य-आधारित स्तंभ सूचकांक |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | निर्दिष्ट स्तंभ की क्षैतिज संरेखण का नया मान |
## टिप्पणी



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## देखें भी

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)