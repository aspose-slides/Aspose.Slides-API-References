---
title: Timer()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรัคเตอร์.
type: docs
weight: 1
url: /th/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | ฟังก์ชันที่จะถูกเรียกโดยตัวจับเวลา. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | ฟังก์ชันที่จะถูกเรียกโดยตัวจับเวลา. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | อาร์กิวเมนต์ของฟังก์ชัน callback. |
| dueTime | **int64_t** | [Timeout](../../timeout/) ก่อนการเรียกครั้งแรกของฟังก์ชัน callback, หน่วยเป็นมิลลิวินาที; ค่าติดลบจะไม่กำหนดเวลาให้ตัวจับเวลาหลังจากการสร้างจึงสามารถกำหนดเวลาใหม่ได้ภายหลัง. |
| period | **int64_t** | [Timeout](../../timeout/) ระหว่างการเรียกต่อเนื่องของฟังก์ชัน callback, หน่วยเป็นมิลลิวินาที; ค่าที่ไม่เป็นบวกหมายความว่าตัวจับเวลาจะทำงานเพียงครั้งเดียว. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | ฟังก์ชันที่จะถูกเรียกโดยตัวจับเวลา. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | อาร์กิวเมนต์ของฟังก์ชัน callback. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ก่อนการเรียกครั้งแรกของฟังก์ชัน callback; ค่าติดลบจะไม่กำหนดเวลาให้ตัวจับเวลาหลังจากการสร้างจึงสามารถกำหนดเวลาใหม่ได้ภายหลัง. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ระหว่างการเรียกต่อเนื่องของฟังก์ชัน callback; ค่าที่ไม่เป็นบวกหมายความว่าตัวจับเวลาจะทำงานเพียงครั้งเดียว. |

## ดูเพิ่มเติม

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)