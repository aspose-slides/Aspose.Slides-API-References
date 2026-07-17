---
title: operator<=()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 2081
url: /zh/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) 函数




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) 函数




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) 函数


始终返回 false。

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) 函数


确定指定的值是否小于或等于由指定的 [Nullable](../nullable/) 对象表示的值，通过对这些值应用 [operator<=()](./)。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 第一个比较值的类型 |
| T2 | 表示第二个比较值的 [Nullable](../nullable/) 对象的底层类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| some | const T1\& | 用作第一个比较值的常量引用 |
| other | const [Nullable](../nullable/)\<T2\>\& | 用作第二个比较值的 [Nullable](../nullable/) 对象的常量引用，该对象的表示值将作为第二个比较值 |

### 返回值

如果第一个比较值小于或等于第二个比较值则为 True，否则为 false

## System::operator<=(std::nullptr_t, TimeSpan) 函数




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## 另见

* 类 [DateTime](../datetime/)
* 类 [DateTimeOffset](../datetimeoffset/)
* 类 [Nullable](../nullable/)
* 类 [TimeSpan](../timespan/)
* 结构体 [IsNullable](../isnullable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)