---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य IMathElement.
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) विधि


निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| index | **int32_t** | प्राप्त करने के लिए आइटम का शून्य-आधारित सूचकांक |
## टिप्पणी



उदाहरण: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathElementCollection](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)