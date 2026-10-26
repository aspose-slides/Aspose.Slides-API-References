---
title: Insert()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट सूचकांक पर संग्रह में IMathBlock डालता है।
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) विधि

निर्दिष्ट सूचकांक पर संग्रह में [IMathBlock](../../imathblock/) सम्मिलित करता है।

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित सूचकांक जहाँ एक आइटम सम्मिलित किया जाना चाहिए। |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | [IMathBlock](../../imathblock/) को सम्मिलित करने के लिए। |
## टिप्पणी



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [IMathBlock](../../imathblock/)
* वर्ग [IMathBlockCollection](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)