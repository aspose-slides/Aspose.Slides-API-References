---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API 参考
description: 特征结构体，用于在参数类型是指针类型时将其转换为弱指针。
type: docs
weight: 1990
url: /zh/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter 结构体

特征结构体，用于在参数类型是指针类型时将其转换为弱指针。

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)