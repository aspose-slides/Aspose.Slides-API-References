---
title: InsertRowAfter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति में सभी तत्व प्रारंभ में null होते हैं।
type: docs
weight: 300
url: /hi/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) विधि

निर्दिष्ट पंक्ति के बाद एक नई पंक्ति डालें। नई पंक्ति में सभी तत्व प्रारंभ में null होते हैं।

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rowIndex | **int32_t** | उस पंक्ति का सूचकांक जिसके बाद नई पंक्ति डालनी है |
## टिप्पणी



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## संबंधित देखें

* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)