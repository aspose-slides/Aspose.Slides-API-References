---
title: get_Count()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह में वास्तविक रूप से शामिल तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int32_t।
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() विधि


कलेक्शन में वास्तविक रूप से शामिल तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य **int32_t**।

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## संबंधित

* वर्ग [IMathBlockCollection](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)