---
title: Item()
second_title: Aspose.Slides for C++ API 参考
description: 获取 ValueTuple 对象组件的值的引用。
type: docs
weight: 14
url: /zh/system/valuetuple/item/
---
## ValueTuple::Item() 方法

获取 [ValueTuple](../) 对象组件的值的引用。

```cpp
template<std::size_t> std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Index | 类应返回的项的编号。 |

## ValueTuple::Item() const 方法

获取 [ValueTuple](../) 对象组件的值。

```cpp
template<std::size_t> const std::tuple_element_t<Index, tuple_t> & System::ValueTuple<Args>::Item() const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Index | 类应返回的项的编号。 |

## 另见

* 类 [ValueTuple](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)