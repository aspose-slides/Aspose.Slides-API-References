---
title: DateTimeOffset()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรักเตอร์เริ่มต้น.
type: docs
weight: 1
url: /th/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() คอนสตรักเตอร์

คอนสตรักเตอร์เริ่มต้น.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | วันที่และเวลา. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ticks | **int64_t** | จำนวน tick. |
| offset | [TimeSpan](../../timespan/) | ออฟเซ็ตของเวลาเมื่อเทียบกับ UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | วันที่และเวลา. |
| offset | [TimeSpan](../../timespan/) | ออฟเซ็ตของเวลาเมื่อเทียบกับ UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปี (1 ถึง 9999). |
| month | int | เดือน (1 ถึง 12). |
| day | int | วัน (1 ถึงจำนวนวันในเดือน). |
| hour | int | ชั่วโมง (0 ถึง 23). |
| minute | int | นาที (0 ถึง 59). |
| second | int | วินาที (0 ถึง 59). |
| offset | [TimeSpan](../../timespan/) | ออฟเซ็ตของเวลาเมื่อเทียบกับ UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปี (1 ถึง 9999). |
| month | int | เดือน (1 ถึง 12). |
| day | int | วัน (1 ถึงจำนวนวันในเดือน). |
| hour | int | ชั่วโมง (0 ถึง 23). |
| minute | int | นาที (0 ถึง 59). |
| second | int | วินาที (0 ถึง 59). |
| millisecond | int | มิลลิวินาที (0 ถึง 999). |
| offset | [TimeSpan](../../timespan/) | ออฟเซ็ตของเวลาเมื่อเทียบกับ UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) คอนสตรักเตอร์

คอนสตรักเตอร์.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปี. |
| month | int | เดือน (1 ถึง 12). |
| day | int | วัน (1 ถึงจำนวนวันในเดือน). |
| hour | int | ชั่วโมง (0 ถึง 23). |
| minute | int | นาที (0 ถึง 59). |
| second | int | วินาที (0 ถึง 59). |
| millisecond | int | มิลลิวินาที (0 ถึง 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | ปฏิทินที่ใช้ในการตีความปี, เดือน, และวัน. |
| offset | [TimeSpan](../../timespan/) | ออฟเซ็ตของเวลาเมื่อเทียบกับ UTC. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [DateTimeOffset](../)
* คลาส [DateTime](../../datetime/)
* คลาส [TimeSpan](../../timespan/)
* คลาส [Calendar](../../../system.globalization/calendar/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)