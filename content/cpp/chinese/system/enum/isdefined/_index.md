---
title: IsDefined()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定的值是否是枚举类型 E 的成员。
type: docs
weight: 27
url: /zh/system/enum/isdefined/
---
## Enum::IsDefined(E) 方法

确定指定的值是否是枚举类型 **E** 的成员。

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | E | 要检查的值 |

### 返回值

如果 **value** 是枚举 **E** 的成员，则为 true；否则为 false

## Enum::IsDefined(T) 方法

确定指定的值是否是枚举类型 **T** 的成员。

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 要检查的值 |

### 返回值

如果 **value** 是枚举 **T** 的成员，则为 true；否则为 false

## Enum::IsDefined(const String\&) 方法

确定具有指定名称的值是否在枚举 **E** 的成员中。

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 要检查的名称 |

### 返回值

如果存在具有指定名称的枚举 **E** 成员，则为 true。

## 另请参见

* Typedef [UnderlyingType](../underlyingtype/)
* 类 [String](../../string/)
* Struct [Enum](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)