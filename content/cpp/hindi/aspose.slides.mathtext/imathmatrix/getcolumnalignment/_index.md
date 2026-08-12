---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट कॉलम का क्षैतिज संरेखन प्राप्त करें
type: docs
weight: 235
url: /hi/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) method

निर्दिष्ट कॉलम का क्षैतिज संरेखन प्राप्त करता है

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | शून्य-आधारित कॉलम इंडेक्स |

### Return Value

निर्दिष्ट कॉलम का क्षैतिज संरेखन
## Remarks



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## See Also

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)