---
title: Reorder()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट आकार को आकार संग्रह में नई स्थिति में ले जाता है।
type: docs
weight: 339
url: /hi/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) विधि

निर्दिष्ट आकार को आकार संग्रह में नई स्थिति में ले जाता है।

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित लक्ष्य सूचकांक जहाँ आकार रखा जाएगा। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | संग्रह में ले जाने के लिए [IShape](../../ishape/)। |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) विधि

निर्दिष्ट आकारों को आकार संग्रह में ले जाता है, उन्हें दिए गए सूचकांक से शुरू करके रखता है।

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित लक्ष्य सूचकांक जहाँ पहला निर्दिष्ट आकार रखा जाएगा; बाद के आकार प्रदान किए क्रम में रखे जाएंगे। |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | संग्रह में ले जाने के लिए एक या अधिक [IShape](../../ishape/) उदाहरण। |

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* वर्ग [IShape](../../ishape/)
* वर्ग [ShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)