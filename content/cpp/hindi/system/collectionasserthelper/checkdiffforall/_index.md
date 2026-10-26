---
title: CheckDiffForAll()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जाँचता है कि सभी संग्रह तत्व प्रेडिकेट का पालन करते हैं।
type: docs
weight: 14
url: /hi/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) विधि

सभी संग्रह तत्वों का प्रेडिकेट के अनुसार होना जाँचता है।

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | जाँचने के लिए प्रेडिकेट। |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | जाँचने के लिए मान। |

### रिटर्न वैल्यू

यदि किसी तत्व के लिए जाँच विफल हो तो False, यदि सभी पास हों तो true।

## और देखें

* टाइपडिफ़ [SharedPtr](../../sharedptr/)
* क्लास [ICollection](../../../system.collections.generic/icollection/)
* स्ट्रक्ट [CollectionAssertHelper](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)