---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से विशिष्ट वस्तु की पहली घटना को हटाता है/>.
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) विधि


विशिष्ट वस्तु की पहली घटना को संग्रह से हटाता है/>।

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | संग्रह से हटाने के लिए वस्तु। |

### वापसी मान

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection/>.

## टिप्पणियाँ



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)