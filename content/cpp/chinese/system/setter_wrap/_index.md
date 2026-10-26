---
title: setter_wrap()
second_title: Aspose.Slides for C++ API 参考
description: 针对带有类型转换的静态 setter 函数的重载。
type: docs
weight: 2783
url: /zh/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) 函数

针对带有类型转换的静态 setter 函数的重载。

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |
| T2 | setter 函数期望的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pSetter | void(*)(T2) | 静态 setter 函数引用。 |
| value | T | 要设置的值。 |

### 返回值

设置的值。

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) 函数

针对带有类型转换的实例 setter 函数的重载。

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |
| T2 | setter 函数期望的类型。 |
| Host | 实例类型。 |
| HostSet | - Host 本身，或其基类，其中定义了属性的 setter。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | Host *const | [Object](../object/) 用于调用 setter 函数的对象。 |
| pSetter | void(HostSet::*)(T2) | setter 函数引用。 |
| value | T | 要设置的值。 |

### 返回值

设置的值。

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)