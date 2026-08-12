---
title: IndexOf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: संग्रह में किसी विशिष्ट IMathBlock का इंडेक्स निर्धारित करता है।
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) विधि


किसी विशिष्ट [IMathBlock](../../imathblock/) का इंडेक्स संग्रह में निर्धारित करता है।

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | संग्रह में स्थित करने के लिए वस्तु। |

### वापसी मान

संग्रह में मिलने पर *item* का इंडेक्स; अन्यथा -1.

## टिप्पणियाँ



```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)