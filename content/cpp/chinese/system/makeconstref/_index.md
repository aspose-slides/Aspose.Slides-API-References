---
title: MakeConstRef
second_title: Aspose.Slides 的 C++ API 参考
description: 特性用于在通用类型为 String 或 SmartPtr<> 类型时生成 \"const reference\"。
type: docs
weight: 1743
url: /zh/system/makeconstref/
---
## MakeConstRef 结构体


特性用于在通用类型为 [String](../string/) 或 SmartPtr<> 类型时生成 \"const reference\"。

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)