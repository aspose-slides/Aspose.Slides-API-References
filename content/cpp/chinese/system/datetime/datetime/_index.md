---
title: DateTime()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个实例，该实例表示等于 MinValue 的最小可能日期和时间值。
type: docs
weight: 1
url: /zh/system/datetime/datetime/
---
## DateTime::DateTime() 构造函数


构造一个实例，该实例表示等于 MinValue 的最小可能日期和时间值。

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) 构造函数


构造一个实例，该实例表示由特定 year、month 和 day 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 构造函数


构造一个实例，该实例表示在指定 calendar 中由特定 year、month 和 day 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用于解释指定 **year**、**month** 和 **day** 的 calendar。 |

## DateTime::DateTime(int, int, int, int, int, int) 构造函数


构造一个实例，该实例表示由特定 year、month、day、hour、minute 和 second 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| hour | int | 正在构造的实例所表示的 **day** 的 hour。 |
| minute | int | 正在构造的实例所表示的 **hour** 的 minute。 |
| second | int | 正在构造的实例所表示的 **minute** 的 second。 |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) 构造函数


构造一个实例，该实例表示由特定 year、month、day、hour、minute 和 second 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| hour | int | 正在构造的实例所表示的 **day** 的 hour。 |
| minute | int | 正在构造的实例所表示的 **hour** 的 minute。 |
| second | int | 正在构造的实例所表示的 **minute** 的 second。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示提供的日期和时间参数是本地时间、UTC 时间或两者都不是的值。 |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 构造函数


构造一个实例，该实例表示在指定 calendar 中由特定 year、month、day、hour、minute 和 second 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| hour | int | 正在构造的实例所表示的 **day** 的 hour。 |
| minute | int | 正在构造的实例所表示的 **hour** 的 minute。 |
| second | int | 正在构造的实例所表示的 **minute** 的 second。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用于解释指定 **year**、**month** 和 **day** 的 calendar。 |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) 构造函数


构造一个实例，该实例表示由特定 year、month、day、hour、minute、second 和 millisecond 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| hour | int | 正在构造的实例所表示的 **day** 的 hour。 |
| minute | int | 正在构造的实例所表示的 **hour** 的 minute。 |
| second | int | 正在构造的实例所表示的 **minute** 的 second。 |
| millisecond | int | 正在构造的实例所表示的 **second** 的 millisecond。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示提供的日期和时间参数是本地时间、UTC 时间或两者都不是的值。 |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) 构造函数


构造一个实例，该实例表示在指定 calendar 中由特定 year、month、day、hour、minute、second 和 millisecond 指定的日期和时间值。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要由正在构造的实例表示的 year。 |
| month | int | 正在构造的实例所表示的 **year** 的 month。 |
| day | int | 正在构造的实例所表示的 **month** 的 day。 |
| hour | int | 正在构造的实例所表示的 **day** 的 hour。 |
| minute | int | 正在构造的实例所表示的 **hour** 的 minute。 |
| second | int | 正在构造的实例所表示的 **minute** 的 second。 |
| millisecond | int | 正在构造的实例所表示的 **second** 的 millisecond。 |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 指示提供的日期和时间参数是本地时间、UTC 时间或两者都不是的值。 |
| calendar | [DateTimeKind](../../datetimekind/) | 用于解释指定 **year**、**month** 和 **day** 的 calendar。 |

## DateTime::DateTime(int64_t, DateTimeKind) 构造函数


构造一个实例，该实例表示以 tick 数量指定的日期和时间值。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ticks | **int64_t** | 自格里历 0001 年 1 月 1 日 00:00:00.000 起已过去的 100 纳秒间隔数。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示 **ticks** 参数是本地时间、UTC 时间或两者都不是的值。 |

## DateTime::DateTime(int64_t, DateTimeKind, bool) 构造函数


构造一个实例，该实例表示以 tick 数量指定的日期和时间值。供内部使用。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ticks | **int64_t** | 自格里历 0001 年 1 月 1 日 00:00:00 起已过去的 100 纳秒间隔数。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示 **ticks** 参数是本地时间、UTC 时间或两者都不是的值。 |
| is_ambiguous_local_dst | **bool** | 如果指定的日期和时间存在歧义且可映射到多个 UTC 时间，则为 true。 |

## DateTime::DateTime(const DateTime&) 构造函数


复制构造一个实例。

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dt | const [DateTime](../)\& | 要从中复制表示的日期和时间值的 [DateTime](../) 类实例 |

## 另见

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)