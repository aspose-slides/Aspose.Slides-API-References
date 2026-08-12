---
title: InsertColumnBefore()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट कॉलम से पहले एक नया कॉलम डालें। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं।
type: docs
weight: 313
url: /hi/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) विधि


निर्दिष्ट कॉलम से पहले एक नया कॉलम सम्मिलित करें। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं।

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| columnIndex | **int32_t** | नए कॉलम को सम्मिलित करने से पहले के कॉलम का सूचकांक |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## संबंधित देखें

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)