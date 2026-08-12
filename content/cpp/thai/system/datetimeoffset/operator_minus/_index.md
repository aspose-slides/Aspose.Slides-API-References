---
title: operator-()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนอินสแตนซ์ใหม่ของคลาส DateTimeOffset ที่แสดงค่าตัววันที่และเวลา ซึ่งเป็นผลของการลบช่วงเวลาที่ระบุออกจากค่าที่ออบเจกต์ปัจจุบันแทนที่
type: docs
weight: 521
url: /th/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const เมธอด

ส่งคืนอินสแตนซ์ใหม่ของคลาส [DateTimeOffset](../) ที่แสดงค่าตัววันที่และเวลา ซึ่งเป็นผลของการลบช่วงเวลา (time span) ที่ระบุออกจากค่าที่ออบเจกต์ปัจจุบันแทนที่

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | ช่วงเวลาเพื่อทำการลบ |

### ค่าที่คืน

อินสแตนซ์ใหม่ของคลาส [DateTimeOffset](../) ที่แสดงค่าตัววันที่และเวลา ซึ่งเป็นผลของการลบ **value** ออกจากค่าที่ออบเจกต์ปัจจุบันแทนที่

## DateTimeOffset::operator-(const DateTimeOffset\&) const เมธอด

ส่งคืนอินสแตนซ์ของคลาส [TimeSpan](../../timespan/) ที่แสดงช่วงเวลาระหว่างค่าตัววันที่และเวลาที่ออบเจกต์ปัจจุบันและออบเจกต์ที่ระบุแทนที่

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | อินสแตนซ์ของคลาส [DateTime](../../datetime/) ที่ทำเครื่องหมายเป็นหนึ่งด้านของช่วงเวลาที่จะคำนวณ |

### ค่าที่คืน

อินสแตนซ์ของคลาส [TimeSpan](../../timespan/) ที่แสดงช่วงเวลาระหว่างค่าตัววันที่และเวลาที่ออบเจกต์ปัจจุบันและ **other**.

## ดูเพิ่มเติม

* คลาส [DateTimeOffset](../)
* คลาส [TimeSpan](../../timespan/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)