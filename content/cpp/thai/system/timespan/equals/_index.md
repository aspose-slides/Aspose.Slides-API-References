---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเป็นเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่
type: docs
weight: 40
url: /th/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const เมธอด


กำหนดว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเป็นเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [TimeSpan](../) | ออบเจ็กต์ [TimeSpan](../) เพื่อเปรียบเทียบกับออบเจ็กต์ปัจจุบัน |

### ค่าที่คืน

เป็นจริงหากออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุแสดงช่วงเวลาเดียวกัน, มิฉะนั้น - เท็จ

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const เมธอด


กำหนดว่าช่วงเวลาที่ออบเจ็กต์ปัจจุบันแสดงเป็นเท่ากับช่วงเวลาที่ออบเจ็กต์ที่ระบุแสดงหรือไม่

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | ออบเจ็กต์ [TimeSpan](../) เพื่อเปรียบเทียบกับออบเจ็กต์ปัจจุบัน |

### ค่าที่คืน

เป็นจริงหากออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุแสดงช่วงเวลาเดียวกัน, มิฉะนั้น - เท็จ

## TimeSpan::Equals(TimeSpan, TimeSpan) เมธอด


คืนค่าเป็นจริงหากออบเจ็กต์ที่ระบุแสดงช่วงเวลาเดียวกัน, มิฉะนั้น - เท็จ

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [TimeSpan](../)
* คลาส [Object](../../object/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)