---
title: Wait()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน หากช่วงเวลาที่กำหนดหมดลง เธรดจะเข้าสู่คิวพร้อมทำงาน สามารถออกจากโดเมนการซิงโครไนซ์ของบริบทที่ซิงโครไนซ์ก่อนรอและคืนค่าโดเมนหลังจากรอเสร็จ ยังไม่ได้ดำเนินการ
type: docs
weight: 53
url: /th/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) เมธอด

ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน หากช่วงเวลาที่กำหนดหมดลง เธรดจะเข้าสู่คิวพร้อมทำงาน สามารถออกจากโดเมนการซิงโครไนซ์ของบริบทที่ซิงโครไนซ์ก่อนรอและคืนค่าโดเมนหลังจากรอเสร็จ ยังไม่ได้ดำเนินการ。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) เมธอด

ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน หากช่วงเวลาที่กำหนดหมดลง เธรดจะเข้าสู่คิวพร้อมทำงาน สามารถออกจากโดเมนการซิงโครไนซ์ของบริบทที่ซิงโครไนซ์ก่อนรอและคืนค่าโดเมนหลังจากรอเสร็จ ยังไม่ได้ดำเนินการ。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) เมธอด

ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน หากช่วงเวลาที่กำหนดหมดลง เธรดจะเข้าสู่คิวพร้อมทำงาน ยังไม่ได้ดำเนินการ。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) เมธอด

ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน หากช่วงเวลาที่กำหนดหมดลง เธรดจะเข้าสู่คิวพร้อมทำงาน ยังไม่ได้ดำเนินการ。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::Wait(const SharedPtr\<Object\>\&) เมธอด

ปลดล็อกวัตถุและบล็อกเธรดปัจจุบันจนกว่าจะได้ล็อกกลับคืน ยังไม่ได้ดำเนินการ。

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Monitor](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)