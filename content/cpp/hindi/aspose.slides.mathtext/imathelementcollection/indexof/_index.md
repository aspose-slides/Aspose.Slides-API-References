---
title: IndexOf()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह में विशिष्ट गणित तत्व का सूचकांक निर्धारित करता है।
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) विधि

किसी विशिष्ट गणित तत्व का संग्रह में सूचकांक निर्धारित करता है।

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह में तत्व को ढूँढने के लिए। |

### रिटर्न मान

यदि संग्रह में पाया जाए तो *item* का सूचकांक; अन्यथा -1।

## टिप्पणियाँ

उदाहरण:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)