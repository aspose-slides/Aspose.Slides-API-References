---
title: SetColumnAlignment()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें
type: docs
weight: 248
url: /hi/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) विधि


निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | शून्य-आधारित कॉलम इंडेक्स |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | निर्दिष्ट कॉलम की क्षैतिज संरेखण का नया मान |
## टिप्पणी



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## देखें

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)