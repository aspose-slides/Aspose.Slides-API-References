---
title: DateTime()
second_title: Aspose.Slides for C++ API リファレンス
description: MinValue に等しい、可能な限り最小の日付と時刻の値を表すインスタンスを構築します。
type: docs
weight: 1
url: /ja/system/datetime/datetime/
---
## DateTime::DateTime() コンストラクタ


最小可能な日付と時刻の値（MinValue に等しい）を表すインスタンスを構築します。

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) コンストラクタ


特定の年、月、日で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) コンストラクタ


指定されたカレンダーで、特定の年、月、日で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### 引数

| Parameter | Type | Description |
| --- ... (same as original but translated) |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 指定された **year**、**month**、**day** を解釈するために使用されるカレンダー。 |

## DateTime::DateTime(int, int, int, int, int, int) コンストラクタ


特定の年、月、日、時、分、秒で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| hour | int | インスタンスが表す **day** の **hour** の値。 |
| minute | int | インスタンスが表す **hour** の **minute** の値。 |
| second | int | インスタンスが表す **minute** の **second** の値。 |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) コンストラクタ


特定の年、月、日、時、分、秒で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| hour | int | インスタンスが表す **day** の **hour** の値。 |
| minute | int | インスタンスが表す **hour** の **minute** の値。 |
| second | int | インスタンスが表す **minute** の **second** の値。 |
| kind | [DateTimeKind](../../datetimekind/) | 提供された日付と時刻のパラメーターがローカル時刻、UTC 時刻、またはそのいずれでもないことを示す値。 |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) コンストラクタ


指定されたカレンダーで、特定の年、月、日、時、分、秒で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| hour | int | インスタンスが表す **day** の **hour** の値。 |
| minute | int | インスタンスが表す **hour** の **minute** の値。 |
| second | int | インスタンスが表す **minute** の **second** の値。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 指定された **year**、**month**、**day** を解釈するために使用されるカレンダー。 |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) コンストラクタ


特定の年、月、日、時、分、秒、ミリ秒で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| hour | int | インスタンスが表す **day** の **hour** の値。 |
| minute | int | インスタンスが表す **hour** の **minute** の値。 |
| second | int | インスタンスが表す **minute** の **second** の値。 |
| millisecond | int | インスタンスが表す **second** の **millisecond** の値。 |
| kind | [DateTimeKind](../../datetimekind/) | 提供された日付と時刻のパラメーターがローカル時刻、UTC 時刻、またはそのいずれでもないことを示す値。 |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) コンストラクタ


指定されたカレンダーで、特定の年、月、日、時、分、秒、ミリ秒で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | インスタンスが表す **year** の値。 |
| month | int | インスタンスが表す **year** の **month** の値。 |
| day | int | インスタンスが表す **month** の **day** の値。 |
| hour | int | インスタンスが表す **day** の **hour** の値。 |
| minute | int | インスタンスが表す **hour** の **minute** の値。 |
| second | int | インスタンスが表す **minute** の **second** の値。 |
| millisecond | int | インスタンスが表す **second** の **millisecond** の値。 |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 提供された日付と時刻のパラメーターがローカル時刻、UTC 時刻、またはそのいずれでもないことを示す値。 |
| calendar | [DateTimeKind](../../datetimekind/) | 指定された **year**、**month**、**day** を解釈するために使用されるカレンダー。 |

## DateTime::DateTime(int64_t, DateTimeKind) コンストラクタ


ティック数で指定された日付と時刻の値を表すインスタンスを構築します。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | グレゴリオ暦で 0001 年 1 月 1 日 00:00:00.000 から経過した 100 ナノ秒単位の間隔数。 |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** パラメーターがローカル時刻、UTC 時刻、またはそのいずれでもないことを示す値。 |

## DateTime::DateTime(int64_t, DateTimeKind, bool) コンストラクタ


ティック数で指定された日付と時刻の値を表すインスタンスを構築します。内部使用用。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | グレゴリオ暦で 0001 年 1 月 1 日 00:00:00 から経過した 100 ナノ秒単位の間隔数。 |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** パラメーターがローカル時刻、UTC 時刻、またはそのいずれでもないことを示す値。 |
| is_ambiguous_local_dst | **bool** | 指定された日付と時刻が曖昧で、複数の UTC 時刻にマッピングできる場合は true。 |

## DateTime::DateTime(const DateTime\&) コンストラクタ


インスタンスをコピー構築します。

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| dt | const [DateTime](../)\& | コピー元となる [DateTime](../) クラスのインスタンス。 |

## 参照

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)