---
title: CastEnumerableTo()
second_title: Aspose.Slides for C++ API 参考
description: 对指定的可枚举对象的元素执行显式类型转换为不同的类型。
type: docs
weight: 2926
url: /zh/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) 函数

对指定的可枚举对象的元素执行显式类型转换为不同的类型。

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| To | 要将可枚举对象的元素静态转换成的类型 |
| From | 可枚举对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumerable | const From\& | 包含要转换的元素的可枚举对象 |

### 返回值

指向新集合的指针，其中包含类型为 **To** 的元素，这些元素等价于 **enumerable** 的元素

## System::CastEnumerableTo(const From\&) 函数

对指定的可枚举对象的元素执行显式类型转换为不同的类型。

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| To | 要将可枚举对象的元素静态转换成的类型 |
| From | 可枚举对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enumerable | const From\& | 是具有已定义 get_Count 方法的 Enumerable 对象的继承者，并包含要转换的元素 |

### 返回值

指向新集合的指针，其中包含类型为 **To** 的元素，这些元素等价于 **enumerable** 的元素

## 另见

* 类 [ListPtr](../../system.collections.generic/listptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)