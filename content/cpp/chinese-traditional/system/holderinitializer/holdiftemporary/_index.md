---
title: HoldIfTemporary()
second_title: Aspose.Slides for C++ API 參考
description: 返回對 rvalue 的引用（const）
type: docs
weight: 14
url: /zh-hant/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) 方法

返回對 rvalue 的引用（const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) 方法

返回對 rvalue 的引用（非 const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) 方法

將傳入的 lvalue 複製到 holder，然後返回 holder 的引用。

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## 另請參閱

* 結構 [HolderInitializer](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)