---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API Reference
description: Serializes two collections for message representation.
type: docs
weight: 53
url: /system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


Serializes two collections for message representation.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | A custom string which is inserted before the expected value in the resulting message |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collection. |

### Return Value

User-friendly message on collections' contents.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)