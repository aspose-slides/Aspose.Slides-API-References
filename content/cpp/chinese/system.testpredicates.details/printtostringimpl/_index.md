---
title: PrintToStringImpl()
second_title: Aspose.Slides C++ API 参考
description: "使用 ToString() 方法将 System::Object 子类打印为字符串。"
type: docs
weight: 14
url: /zh/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) 函数

使用 ToString() 方法将 [System::Object](../../system/object/) 子类打印为字符串。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 最终类类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | 指向要打印的对象的指针。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

[String](../../system/string/) 表示传入对象的表示，若 **value** 为 null 则返回 "nullptr"。

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) 函数

使用 ToString() 方法将 [System::Object](../../system/object/) 子类打印为字符串。

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 最终类类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | 指向要打印的对象的指针。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

[String](../../system/string/) 表示传入对象的表示，若 **value** 为 null 则返回 "nullptr"。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 函数

使用 ToString() 方法将对象打印为字符串。

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

[String](../../system/string/) 表示传入对象的表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 函数

使用 PrintTo 方法将对象打印为字符串。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

[String](../../system/string/) 表示传入对象的表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 函数

使用 PrintTo 方法将对象打印为字符串。

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

[String](../../system/string/) 表示传入对象的表示。

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) 函数

将 pair 打印为字符串。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个 pair 类型参数。 |
| T2 | 第二个 pair 类型参数。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

第一个和第二个 pair 组件的联合字符串表示。

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) 函数

将 pair 打印为字符串。

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个 pair 类型参数。 |
| T2 | 第二个 pair 类型参数。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

第一个和第二个 pair 组件的联合字符串表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) 函数

通过打印其元素（不超过 32 个），将 STL 风格的容器打印为字符串。

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) 用于打印。 |
| s | long long | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

包含元素的联合字符串表示。

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) 函数

使用 gtest 提供的函数将其他类型打印为字符串。

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |
| s | int | 服务参数，用作基于此参数类型的函数重载选择器；该参数的值被忽略。 |

### 返回值

传入对象的 [String](../../system/string/) 表示。

## 另见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [WeakPtr](../../system/weakptr/)
* 类 [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* 类 [Object](../../system/object/)
* 结构体 [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* 结构体 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 结构体 [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* 命名空间 [System::TestPredicates::Details](../)
* 库 [Aspose.Slides](../../)