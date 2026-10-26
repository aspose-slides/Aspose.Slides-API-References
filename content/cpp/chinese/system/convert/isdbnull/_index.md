---
title: IsDBNull()
second_title: Aspose.Slides C++ API 参考
description: 未实现。
type: docs
weight: 14
url: /zh/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) 方法


未实现。

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```


## Convert::IsDBNull(const SharedPtr\<T\>\&) 方法


未实现。假的实现，检查值是否为 nullptr。

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## 另见

* 类型定义 [SharedPtr](../../sharedptr/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)