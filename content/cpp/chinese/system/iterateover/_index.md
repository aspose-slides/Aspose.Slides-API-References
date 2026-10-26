---
title: IterateOver()
second_title: Aspose.Slides for C++ API 参考
description: "此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对没有 begin()、end() 方法的 Enumerable，使用目标类型参数，例如 (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2432
url: /zh/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对没有 begin()、end() 方法的 Enumerable，使用目标类型参数，例如 (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型，必须从迭代器返回 |
| Enumerable | 被包装对象的类型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对没有 begin()、end() 方法的 Enumerable，使用默认目标类型参数，例如 (auto& value : IterateOver(enumerable))，相当于以下 C# 代码 foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Enumerable | 被包装对象的类型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对具有 begin()、end() 方法的 Enumerable，使用默认目标类型参数，例如 (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Enumerable | 被包装对象的类型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对具有 begin()、end() 方法的 Enumerable，目标类型与迭代器的原始 value_type 相同。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Enumerable | 被包装对象的类型 |
| T | 必须从迭代器返回的目标类型 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对具有 begin()、end() 方法的 Enumerable，目标类型与迭代器的原始 value_type 不同。

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Enumerable | 被包装对象的类型 |
| T | 必须从迭代器返回的目标类型 |

## System::IterateOver(const Enumerable *) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对 Enumerable，使用默认目标类型。

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Enumerable | 被包装对象的类型 |

## System::IterateOver(const Enumerable *) 函数

此函数属性包装可枚举（或可迭代）对象，以便可以在基于范围的 for 循环中使用。此重载针对没有 begin()、end() 方法的 Enumerable，使用目标类型参数，例如 (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型，必须从迭代器返回 |
| Enumerable | 被包装对象的类型 |

## 另请参见

* 类 [SmartPtr](../smartptr/)
* 结构体 [IsSmartPtr](../issmartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)