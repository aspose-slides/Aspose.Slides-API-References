---
title: Join()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เข้าร่วมเธรดที่จัดการ. ทำการรอโดยไม่จำกัดหากจำเป็น.
type: docs
weight: 196
url: /th/system.threading/thread/join/
---
## Thread::Join() เมธอด

เข้าร่วมเธรดที่จัดการ. ทำการรอโดยไม่จำกัดหากจำเป็น.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) เมธอด

เข้าร่วมเธรดที่จัดการ. ทำการรอโดยจำกัด.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | ระยะเวลารอเป็นมิลลิวินาที. |

### ค่าที่คืน

True หากเธรดเข้าร่วมสำเร็จ, false หากเวลาหมด.

## Thread::Join(TimeSpan) เมธอด

เข้าร่วมเธรดที่จัดการ. ทำการรอโดยจำกัด.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [TimeSpan](../../../system/timespan/) ที่กำหนดจำนวนเวลาที่รอให้เธรดสิ้นสุด. |

### ค่าที่คืน

True หากเธรดเข้าร่วมสำเร็จ, false หากเวลาหมด.

## ดูเพิ่มเติม

* คลาส [Thread](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)