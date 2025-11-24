---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 92
url: /system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) method




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) method


Deconstructs object to this value tuple.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | An object to deconstruct |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [ValueTuple](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)