---
title: ToArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक एरे बनाता है और लौटाता है जिसमें सभी आकृतियां सम्मिलित होती हैं।
type: docs
weight: 326
url: /hi/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() मेथड

सभी आकृतियों को सम्मिलित करने वाला एक एरे बनाता है और लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### वापसी मान

एक एरे [IShape](../../ishape/) ऑब्जेक्ट्स का।

## ShapeCollection::ToArray(int32_t, int32_t) मेथड

निर्दिष्ट रेंज में सभी आकृतियों को सम्मिलित करने वाला एरे बनाता है और लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | वापस करने हेतु पहली आकृति का इंडेक्स। |
| count | **int32_t** | वापस करने हेतु आकृतियों की संख्या। |

### वापसी मान

एक एरे [IShape](../../ishape/) ऑब्जेक्ट्स का।

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [ShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)