---
title: RemoveAt()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह में निर्दिष्ट अनुक्रमांक पर वस्तु को हटाता है।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) विधि

संग्रह में निर्दिष्ट अनुक्रमांक पर वस्तु को हटाता है।

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | हटाने वाली वस्तु का शून्य-आधारित अनुक्रमांक। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## देखें

* क्लास [IMathBlockCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)