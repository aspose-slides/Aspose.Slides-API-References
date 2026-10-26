---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API 参考
description: 翻译器将针对已定义 setter 和 getter 的类属性的 C# 增量表达式转换为对该函数的调用。
type: docs
weight: 2796
url: /zh/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) 函数


翻译器将 C# 的增量表达式（针对已定义 setter 和 getter 的类属性）转换为对该函数的调用。

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
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

属性的递增值

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 函数


翻译器将 C# 的增量表达式（针对已定义 setter 和 getter 的类属性）转换为对该函数的调用。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 属性的类型 |
| Host | - 要修改的实例的类 |
| HostGet | - Host 本身或其基类型，属性的 getter 定义所在 |
| HostSet | - Host 本身或其基类型，属性的 setter 定义所在 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | Host *const | 指向要递增其属性的对象的指针 |
| pGetter | T(HostGet::*)() | 指向属性的 getter 方法的函数指针 |
| pSetter | void(HostSet::*)(T) | 指向属性的 setter 方法的函数指针 |

### 返回值

属性的递增值

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)