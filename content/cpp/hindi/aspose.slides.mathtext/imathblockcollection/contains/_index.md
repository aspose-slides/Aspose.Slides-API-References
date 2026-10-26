---
title: Contains()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं।
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) विधि


निर्धारित करता है कि संग्रह में कोई विशिष्ट मान मौजूद है या नहीं।

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | संग्रह में स्थित करने के लिए वस्तु। |

### रिटर्न वैल्यू

true यदि *item* संग्रह में पाया जाता है; अन्यथा false.

## टिप्पणी



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)