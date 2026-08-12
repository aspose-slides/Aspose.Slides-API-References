---
title: ToArray()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: सभी स्लाइड्स के साथ एक ऐरे बनाता है और उसे वापस लौटाता है।
type: docs
weight: 92
url: /hi/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() विधि


सभी स्लाइड्स के साथ एक ऐरे बनाता है और लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```


### रिटर्न वैल्यू

[ISlide](../../islide/) का ऐरे

## ISlideCollection::ToArray(int32_t, int32_t) विधि


निर्दिष्ट रेंज की सभी स्लाइड्स के साथ एक ऐरे बनाता है और लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | पहली स्लाइड को जोड़ने का इंडेक्स। |
| count | **int32_t** | जोड़ने के लिए स्लाइड्स की संख्या। |

### रिटर्न वैल्यू

[ISlide](../../islide/) का ऐरे

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)