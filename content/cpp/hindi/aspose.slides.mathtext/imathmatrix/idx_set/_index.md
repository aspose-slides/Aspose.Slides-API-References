---
title: idx_set()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मैट्रिक्स के तत्व
type: docs
weight: 222
url: /hi/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) विधि

मैट्रिक्स के तत्व

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| row | **int32_t** | पंक्ति का शून्य-आधारित अनुक्रमणिका, जिसका आइटम प्राप्त करना है |
| column | **int32_t** | स्तंभ का शून्य-आधारित अनुक्रमणिका, जिसका आइटम प्राप्त करना है |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)