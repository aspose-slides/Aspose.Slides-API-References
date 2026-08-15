---
title: IsDBNull()
second_title: Aspose.Slides for C++ API 參考
description: 未實作。
type: docs
weight: 14
url: /zh-hant/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) 方法

未實作。

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```

## Convert::IsDBNull(const SharedPtr\<T\>\&) 方法

未實作 虛擬實作，檢查值是否為 nullptr。

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## 另請參閱

* 型別別名 [SharedPtr](../../sharedptr/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 結構 [Convert](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)