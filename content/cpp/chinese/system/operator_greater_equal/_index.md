---
title: operator>=()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 2107
url: /zh/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) 函数




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) 函数




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) 函数


始终返回 false。

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) 函数


确定指定的值是否大于或等于由指定的 [Nullable](../nullable/) 对象表示的值，方法是对这些值应用 [operator>=()](./)。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### 返回值

如果第一个比较项大于或等于第二个比较项则返回 True，否则返回 false

## System::operator>=(std::nullptr_t, TimeSpan) 函数




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## 另见

* 类 [DateTime](../datetime/)
* 类 [DateTimeOffset](../datetimeoffset/)
* 类 [Nullable](../nullable/)
* 类 [TimeSpan](../timespan/)
* 结构体 [IsNullable](../isnullable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)