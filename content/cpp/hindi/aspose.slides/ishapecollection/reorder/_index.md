---
title: Reorder()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट आकार को आकार संग्रह के भीतर नई स्थिति में ले जाता है।
type: docs
weight: 300
url: /hi/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) विधि

निर्दिष्ट आकार को आकार संग्रह में नई स्थिति में ले जाता है।

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सफ़्र-आधारित लक्ष्य इंडेक्स जहाँ आकार रखा जाएगा। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | संग्रह में स्थानांतरित करने के लिए [IShape](../../ishape/)। |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) विधि

निर्दिष्ट आकारों को आकार संग्रह के भीतर ले जाता है, उन्हें दिए गए इंडेक्स से शुरू करके रखता है।

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | सफ़्र-आधारित लक्ष्य इंडेक्स जहाँ पहला निर्दिष्ट आकार रखा जाएगा; बाद के आकार प्रदान किए क्रम में अनुसरण करेंगे। |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | संग्रह में स्थानांतरित करने के लिए एक या अधिक [IShape](../../ishape/) उदाहरण। |

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [IShape](../../ishape/)
* क्लास [IShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)