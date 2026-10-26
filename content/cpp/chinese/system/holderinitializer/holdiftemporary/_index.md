---
title: HoldIfTemporary()
second_title: Aspose.Slides C++ API 参考
description: 返回对右值的引用（const）
type: docs
weight: 14
url: /zh/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) 方法

返回对右值的引用（const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) 方法

返回对右值的引用（非 const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) 方法

将传入的左值复制到 holder，然后返回 holder 的引用。

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## 另请参见

* 结构体 [HolderInitializer](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)