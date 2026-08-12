---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह के अंत में एक गणितीय तत्व जोड़ता है।
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) विधि

कलेक्शन के अंत में एक गणितीय तत्व जोड़ता है।

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह के अंत में जोड़ी जाने वाला [IMathElement](../../imathelement/)। |
## टिप्पणी

उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)