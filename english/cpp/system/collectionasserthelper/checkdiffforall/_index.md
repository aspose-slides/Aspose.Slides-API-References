---
title: CheckDiffForAll()
second_title: Aspose.Slides for C++ API Reference
description: Checks that all collection elements adhere the predicate.
type: docs
weight: 14
url: /cpp/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) method


Checks that all collection elements adhere the predicate.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicate to check. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Values to check. |

### Return Value

False if check fails for any element, true if all pass.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)