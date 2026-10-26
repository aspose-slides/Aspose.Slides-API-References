---
title: ToArray()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सभी शैप्स को सम्मिलित करने वाला एक ऐरे बनाता है और लौटाता है।
type: docs
weight: 287
url: /hi/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() method

सभी शैप्स को सम्मिलित करने वाला एक ऐरे बनाता है और लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### रिटर्न वैल्यू

एक [IShape](../../ishape/) ऑब्जेक्ट्स की ऐरे।

## IShapeCollection::ToArray(int32_t, int32_t) method

निर्दिष्ट रेंज में सभी शैप्स को सम्मिलित करने वाला एक ऐरे बनाता है और लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | पहले शैप्स का सूचकांक जिसे लौटाना है। |
| count | **int32_t** | लौटाने के लिये शैप्स की संख्या। |

### रिटर्न वैल्यू

एक [IShape](../../ishape/) ऑब्जेक्ट्स की ऐरे।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [IShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)