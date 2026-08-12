---
title: Add()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: कलेक्शन के अंत में IMathBlock जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) विधि

कलेक्शन के अंत में [IMathBlock](../../imathblock/) जोड़ता है।

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | एक गणितीय ब्लॉक जो कलेक्शन के अंत में जोड़ा जाएगा |
## टिप्पणी

उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)