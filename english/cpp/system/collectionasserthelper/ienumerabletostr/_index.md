---
title: IEnumerableToStr()
second_title: Aspose.Slides for C++ API Reference
description: Converts collection to string by joining string representations of elements.
type: docs
weight: 40
url: /cpp/system/collectionasserthelper/ienumerabletostr/
---
## CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&) method


Converts collection to string by joining string representations of elements.

```cpp
template<typename T> static System::String System::CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr<System::Collections::Generic::IEnumerable<T>> &ie)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Collection element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ie | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | Collection to check. |

### Return Value

Joint values of collection.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)