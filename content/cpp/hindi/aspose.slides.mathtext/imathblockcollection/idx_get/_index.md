---
title: idx_get()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट इंडेक्स पर वस्तु प्राप्त करता है। केवल पढ़ने योग्य IMathBlock.
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) विधि

निर्दिष्ट इंडेक्स पर वस्तु प्राप्त करता है। केवल पढ़ने योग्य [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | वस्तु को प्राप्त करने के लिए शून्य-आधारित इंडेक्स |

### वापसी मान

गणितीय पाठ का ब्लॉक।

## टिप्पणियाँ



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)