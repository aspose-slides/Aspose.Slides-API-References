---
title: ValueType
second_title: Aspose.Slides for C++ API Reference
description: "Storage type of pointed array. Only meaningful if T is a specialization of System::Array."
type: docs
weight: 508
url: /cpp/system/smartptr/valuetype/
---
## ValueType typedef


Storage type of pointed array. Only meaningful if T is a specialization of [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
