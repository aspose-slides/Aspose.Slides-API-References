---
title: ValueType
second_title: Aspose.Slides C++ API 参考
description: "指向数组的存储类型。仅当 T 是 System::Array 的特化时才有意义。"
type: docs
weight: 508
url: /zh/system/smartptr/valuetype/
---
## ValueType typedef

指向数组的存储类型。仅当 T 是 [System::Array](../../array/) 的特化时才有意义。

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## 参见

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)