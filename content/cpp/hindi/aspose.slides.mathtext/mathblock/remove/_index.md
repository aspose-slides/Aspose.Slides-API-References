---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) विधि

संग्रह से एक विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह से हटाने के लिये वस्तु। |

### रिटर्न मान

true यदि *item* को संग्रह से सफलतापूर्वक हटाया गया; अन्यथा false। यह विधि false भी लौटाती है यदि *item* मूल संग्रह में नहीं पाया जाता।

## टिप्पणियां

उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)