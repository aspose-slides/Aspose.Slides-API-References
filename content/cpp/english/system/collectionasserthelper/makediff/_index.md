---
title: MakeDiff()
second_title: Aspose.Slides for C++ API Reference
description: Calculates 'diff' between two collections. For every element of each collection as key resulting value will be positive if element occures more times in \"expected\" collection, negative if element occures more times in \"actual\" collection, and zero if element occures equal times in each collection.
type: docs
weight: 1
url: /system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


Calculates 'diff' between two collections. For every element of each collection as key resulting value will be positive if element occures more times in \"expected\" collection, negative if element occures more times in \"actual\" collection, and zero if element occures equal times in each collection.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collecion. |

### Return Value

Map of per-value comparison results as per rules above.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)