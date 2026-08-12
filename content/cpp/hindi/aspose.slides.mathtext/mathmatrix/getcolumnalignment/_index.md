---
title: GetColumnAlignment()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट कॉलम का क्षैतिज संरेखण प्राप्त करें
type: docs
weight: 248
url: /hi/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) मेथड

निर्दिष्ट कॉलम का क्षैतिज संरेखण प्राप्त करें

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | शून्य-आधारित कॉलम सूचकांक |

### वापसी मान

निर्दिष्ट कॉलम का क्षैतिज संरेखण

## टिप्पणियाँ



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## संबंधित देखें

* एन्युम [MathHorizontalAlignment](../../mathhorizontalalignment/)
* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)