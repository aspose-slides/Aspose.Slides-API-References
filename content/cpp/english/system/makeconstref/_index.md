---
title: MakeConstRef
second_title: Aspose.Slides for C++ API Reference
description: Trait to make generic type \"const reference\" if it is String or a SmartPtr<> type.
type: docs
weight: 1717
url: /system/makeconstref/
---
## MakeConstRef struct


Trait to make generic type \"const reference\" if it is [String](../string/) or a SmartPtr<> type.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)