---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें। प्रारंभिक रूप से नई पंक्ति के सभी तत्व null होते हैं।
type: docs
weight: 274
url: /hi/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) विधि

निर्दिष्ट पंक्ति से पहले एक नई पंक्ति डालें। नई पंक्ति के सभी तत्व प्रारंभिक रूप से null होते हैं।

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### परिमाण

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | **int32_t** | उस पंक्ति का अनुक्रमणिका जिसके पहले नई पंक्ति डालनी है |
## टिप्पणी



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## देखें

* क्लास [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)