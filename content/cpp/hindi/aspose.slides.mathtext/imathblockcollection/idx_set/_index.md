---
title: idx_set()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: निर्दिष्ट सूचकांक पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य IMathBlock.
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) मेथड


निर्दिष्ट सूचकांक पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | प्राप्त करने वाले आइटम का शून्य-आधारित सूचकांक |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | गणितीय पाठ का ब्लॉक |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)