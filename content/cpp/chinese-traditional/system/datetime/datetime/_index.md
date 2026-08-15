---
title: DateTime()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個表示等於 MinValue 的最小可能日期與時間值的實例。
type: docs
weight: 1
url: /zh-hant/system/datetime/datetime/
---
## DateTime::DateTime() 建構子

建立一個表示等於 MinValue 的最小可能日期與時間值的實例。

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) 建構子

建立一個表示指定為特定年份、月份與日期的日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 建構子

建立一個表示於指定曆法中，以特定年份、月份與日期為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用於詮釋指定 **year**、**month** 與 **day** 的曆法。 |

## DateTime::DateTime(int, int, int, int, int, int) 建構子

建立一個表示以特定年份、月份、日期、時、分、秒為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| hour | int | 將由被建構的實例所表示的 **day** 的 **hour**。 |
| minute | int | 將由被建構的實例所表示的 **hour** 的 **minute**。 |
| second | int | 將由被建構的實例所表示的 **minute** 的 **second**。 |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) 建構子

建立一個表示以特定年份、月份、日期、時、分、秒為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| hour | int | 將由被建構的實例所表示的 **day** 的 **hour**。 |
| minute | int | 將由被建構的實例所表示的 **hour** 的 **minute**。 |
| second | int | 將由被建構的實例所表示的 **minute** 的 **second**。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示提供的日期與時間參數是本地時間、UTC 時間或兩者皆非的值。 |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) 建構子

建立一個表示於指定曆法中，以特定年份、月份、日期、時、分、秒為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| hour | int | 將由被建構的實例所表示的 **day** 的 **hour**。 |
| minute | int | 將由被建構的實例所表示的 **hour** 的 **minute**。 |
| second | int | 將由被建構的實例所表示的 **minute** 的 **second**。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用於詮釋指定 **year**、**month** 與 **day** 的曆法。 |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) 建構子

建立一個表示以特定年份、月份、日期、時、分、秒與毫秒為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| hour | int | 將由被建構的實例所表示的 **day** 的 **hour**。 |
| minute | int | 將由被建構的實例所表示的 **hour** 的 **minute**。 |
| second | int | 將由被建構的實例所表示的 **minute** 的 **second**。 |
| millisecond | int | 將由被建構的實例所表示的 **second** 的 **millisecond**。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示提供的日期與時間參數是本地時間、UTC 時間或兩者皆非的值。 |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) 建構子

建立一個表示於指定曆法中，以特定年份、月份、日期、時、分、秒與毫秒為指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 將由被建構的實例所表示的 **year**。 |
| month | int | 將由被建構的實例所表示的 **year** 的 **month**。 |
| day | int | 將由被建構的實例所表示的 **month** 的 **day**。 |
| hour | int | 將由被建構的實例所表示的 **day** 的 **hour**。 |
| minute | int | 將由被建構的實例所表示的 **hour** 的 **minute**。 |
| second | int | 將由被建構的實例所表示的 **minute** 的 **second**。 |
| millisecond | int | 將由被建構的實例所表示的 **second** 的 **millisecond**。 |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 指示提供的日期與時間參數是本地時間、UTC 時間或兩者皆非的值。 |
| calendar | [DateTimeKind](../../datetimekind/) | 用於詮釋指定 **year**、**month** 與 **day** 的曆法。 |

## DateTime::DateTime(int64_t, DateTimeKind) 建構子

建立一個以刻度數指定之日期與時間值的實例。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ticks | **int64_t** | 自格里曆 0001 年 1 月 1 日 00:00:00.000 起所經過的 100 奈秒間隔數。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示 **ticks** 參數是本地時間、UTC 時間或兩者皆非的值。 |

## DateTime::DateTime(int64_t, DateTimeKind, bool) 建構子

建立一個以刻度數指定之日期與時間值的實例。供內部使用。

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ticks | **int64_t** | 自格里曆 0001 年 1 月 1 日 00:00:00.000 起所經過的 100 奈秒間隔數。 |
| kind | [DateTimeKind](../../datetimekind/) | 指示 **ticks** 參數是本地時間、UTC 時間或兩者皆非的值。 |
| is_ambiguous_local_dst | **bool** | 若指定的日期時間存在歧義且可映射至多個 UTC 時間，則為 true。 |

## DateTime::DateTime(const DateTime\&) 建構子

複製建構一個實例。

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dt | const [DateTime](../)\& | 用於從 [DateTime](../) 類別複製所表示之日期與時間值的實例 |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [DateTime](../)
* 類別 [Calendar](../../../system.globalization/calendar/)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)