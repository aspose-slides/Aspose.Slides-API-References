---
title: IndexOf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: किसी विशिष्ट गणितीय तत्व का संग्रह में सूचकांक निर्धारित करता है।
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) विधि


किसी विशिष्ट गणितीय तत्व का संग्रह में सूचकांक निर्धारित करता है।

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह में खोजने के लिए तत्व। |

### रिटर्न मान

यदि *item* संग्रह में पाया जाता है तो उसका सूचकांक; अन्यथा -1.

## टिप्पणी



उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)