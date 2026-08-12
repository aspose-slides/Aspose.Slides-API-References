---
title: InsertRowAfter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। प्रारंभ में नई पंक्ति के सभी तत्व शून्य होते हैं।
type: docs
weight: 287
url: /hi/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) विधि

निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। प्रारंभ में नई पंक्ति के सभी तत्व शून्य होते हैं।

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rowIndex | **int32_t** | उस पंक्ति का सूचकांक जिसके बाद नई पंक्ति डालनी है |
## टिप्पणियाँ

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## संबंधित देखें

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)