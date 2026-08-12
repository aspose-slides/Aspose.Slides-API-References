---
title: DateTime()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่เล็กที่สุดที่เป็นไปได้ซึ่งเท่ากับ MinValue.
type: docs
weight: 1
url: /th/system/datetime/datetime/
---
## DateTime::DateTime() คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาเล็กที่สุดที่เป็นไปได้ซึ่งเท่ากับ MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน และวันเฉพาะ

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน และวันในปฏิทินที่กำหนด

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | ปฏิทินที่ใช้ในการตีความ **year** , **month** และ **day** ที่ระบุ |

## DateTime::DateTime(int, int, int, int, int, int) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน วัน ชั่วโมง นาที และวินาที

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| hour | int | ชั่วโมงของ **day** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| minute | int | นาทีของ **hour** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| second | int | วินาทีของ **minute** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน วัน ชั่วโมง นาที และวินาที

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| hour | int | ชั่วโมงของ **day** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| minute | int | นาทีของ **hour** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| second | int | วินาทีของ **minute** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| kind | [DateTimeKind](../../datetimekind/) | ค่าที่บ่งบอกว่าพารามิเตอร์วันที่และเวลาที่ให้มาระบุเป็นเวลาในท้องถิ่น เวลามาตรฐาน UTC หรือไม่มี |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน วัน ชั่วโมง นาที และวินาทีในปฏิทินที่กำหนด

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| hour | int | ชั่วโมงของ **day** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| minute | int | นาทีของ **hour** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| second | int | วินาทีของ **minute** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | ปฏิทินที่ใช้ในการตีความ **year** , **month** และ **day** ที่ระบุ |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน วัน ชั่วโมง นาที วินาที และมิลลิวินาที

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| hour | int | ชั่วโมงของ **day** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| minute | int | นาทีของ **hour** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| second | int | วินาทีของ **minute** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| millisecond | int | มิลลิวินาทีของ **second** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| kind | [DateTimeKind](../../datetimekind/) | ค่าที่บ่งบอกว่าพารามิเตอร์วันที่และเวลาที่ให้มาระบุเป็นเวลาในท้องถิ่น เวลามาตรฐาน UTC หรือไม่มี |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุโดยปี เดือน วัน ชั่วโมง นาที วินาที และมิลลิวินาทีในปฏิทินที่กำหนด

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| year | int | ปีที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| month | int | เดือนของ **year** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| day | int | วันที่ของ **month** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| hour | int | ชั่วโมงของ **day** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| minute | int | นาทีของ **hour** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| second | int | วินาทีของ **minute** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| millisecond | int | มิลลิวินาทีของ **second** ที่อินสแตนซ์ที่กำลังสร้างจะเป็นตัวแทน |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | ค่าที่บ่งบอกว่าพารามิเตอร์วันที่และเวลาที่ให้มาระบุเป็นเวลาในท้องถิ่น เวลามาตรฐาน UTC หรือไม่มี |
| calendar | [DateTimeKind](../../datetimekind/) | ปฏิทินที่ใช้ในการตีความ **year** , **month** และ **day** ที่ระบุ |

## DateTime::DateTime(int64_t, DateTimeKind) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุเป็นจำนวน Tick

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ticks | **int64_t** | จำนวนช่วง 100-ns ที่ผ่านมาตั้งแต่วันที่ 1 มกราคม ค.ศ. 0001 เวลา 00:00:00.000 ตามปฏิทินเกรกอเรียน |
| kind | [DateTimeKind](../../datetimekind/) | ค่าที่บ่งบอกว่าพารามิเตอร์ **ticks** ระบุเป็นเวลาในท้องถิ่น เวลามาตรฐาน UTC หรือไม่มี |

## DateTime::DateTime(int64_t, DateTimeKind, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แสดงค่าวันที่และเวลาที่ระบุเป็นจำนวน Tick สำหรับการใช้ภายใน

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ticks | **int64_t** | จำนวนช่วง 100-ns ที่ผ่านมาตั้งแต่วันที่ 1 มกราคม ค.ศ. 0001 เวลา 00:00:00.000 ตามปฏิทินเกรกอเรียน |
| kind | [DateTimeKind](../../datetimekind/) | ค่าที่บ่งบอกว่าพารามิเตอร์ **ticks** ระบุเป็นเวลาในท้องถิ่น เวลามาตรฐาน UTC หรือไม่มี |
| is_ambiguous_local_dst | **bool** | true หากวันที่และเวลาที่ระบุเป็นค่าไม่แน่นอนและอาจแมปไปยังหลายค่าเวลา UTC |

## DateTime::DateTime(const DateTime\&) คอนสตรัคเตอร์

คัดลอกสร้างอินสแตนซ์

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dt | const [DateTime](../)\& | อินสแตนซ์ของคลาส [DateTime](../) เพื่อคัดลอกค่าที่แสดงวันและเวลา |

## ดูเพิ่มเติม

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)