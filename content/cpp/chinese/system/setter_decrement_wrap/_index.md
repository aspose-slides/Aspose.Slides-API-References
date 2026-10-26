---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API 参考
description: 翻译器将 C# 的前递减表达式（针对已定义 setter 和 getter 的类属性）转换为对该函数的调用。
type: docs
weight: 2822
url: /zh/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) 函数

翻译器将 C# 的前递减表达式（针对已定义 setter 和 getter 的类属性）转换为对该函数的调用。

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 属性的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pGetter | T(*)() | 指向属性的 getter 自由函数的函数指针 |
| pSetter | void(*)(T) | 指向属性的 setter 自由函数的函数指针 |

### 返回值

属性在递增前的值

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 函数

翻译器将 C# 的前递减表达式（针对已定义 setter 和 getter 的实例属性）转换为对该函数的调用（针对非常量 getter 的重载）。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 属性的类型。 |
| Host | - 要修改的实例的类 |
| HostGet | - Host 本身或其基类，其中定义了属性的 getter |
| HostSet | - Host 本身或其基类，其中定义了属性的 setter |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | Host *const | 要调用 getter 和 setter 的实例。 |
| pGetter | T(HostGet::*)() | 指向属性的 getter 函数的函数指针 |
| pSetter | void(HostSet::*)(T) | 指向属性的 setter 函数的函数指针 |

### 返回值

属性在递增前的值

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 函数

翻译器将 C# 的前递减表达式（针对已定义 setter 和 getter 的实例属性）转换为对该函数的调用（针对 const getter 的重载）。

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 属性的类型。 |
| Host | - 要修改的实例的类 |
| HostConstGet | - Host 本身或其基类，其中定义了属性的 getter |
| HostSet | - Host 本身或其基类，其中定义了属性的 setter |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | Host *const | 要调用 getter 和 setter 的实例。 |
| pGetter | T(HostConstGet::*)() const | 指向属性的 getter 函数的函数指针 |
| pSetter | void(HostSet::*)(T) | 指向属性的 setter 函数的函数指针 |

### 返回值

属性在递增前的值

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)