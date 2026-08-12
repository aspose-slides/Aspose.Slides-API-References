---
title: Clear()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: संग्रह से सभी तत्वों को हटाता है।
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() विधि


संग्रह से सभी तत्वों को हटाता है।

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## देखें

* क्लास [IMathBlockCollection](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)