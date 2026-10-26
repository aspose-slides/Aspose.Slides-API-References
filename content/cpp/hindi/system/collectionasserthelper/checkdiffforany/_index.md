---
title: CheckDiffForAny()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जाँचता है कि कोई भी संग्रह तत्व प्रेडिकेट का पालन करता है।
type: docs
weight: 27
url: /hi/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) विधि

जांचता है कि कोई भी संग्रह तत्व प्रेडिकेट का पालन करता है।

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicate to check. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Values to check. |

### रिटर्न वैल्यू

True यदि जाँच किसी भी तत्व के लिए सफल होती है, false यदि सभी पास होते हैं।

## देखें

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)