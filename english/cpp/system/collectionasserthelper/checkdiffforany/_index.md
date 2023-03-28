---
title: CheckDiffForAny()
second_title: Aspose.Slides for C++ API Reference
description: Checks that any collection element adheres the predicate.
type: docs
weight: 27
url: /cpp/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) method


Checks that any collection element adheres the predicate.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicate to check. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Values to check. |

### Return Value

True if check suceeds for any element, false if all pass.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
