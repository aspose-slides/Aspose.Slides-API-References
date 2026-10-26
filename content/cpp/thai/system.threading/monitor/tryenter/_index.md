---
title: TryEnter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: พยายามที่จะได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุ ไม่ได้ดำเนินการ.
type: docs
weight: 27
url: /th/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) เมธอด

พยายามที่จะได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุ ไม่ได้ดำเนินการ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) เมธอด

พยายามที่จะได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุและตั้งค่าที่บ่งชี้ว่าล็อกถูกจับหรือไม่อย่างอะตอมิก.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) เมธอด

พยายาม, ตามจำนวนมิลลิวินาทีที่ระบุ, เพื่อได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุ ไม่ได้ดำเนินการ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) เมธอด

พยายาม, ตามช่วงเวลาที่ระบุ, เพื่อได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุ ไม่ได้ดำเนินการ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) เมธอด

พยายาม, ตามช่วงเวลาที่ระบุ, เพื่อได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุและตั้งค่าที่บ่งชี้ว่าล็อกถูกจับหรือไม่อย่างอะตอมิก.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) เมธอด

พยายาม, ตามช่วงเวลาที่ระบุ, เพื่อได้ล็อกแบบเอกสิทธิ์บนอ็อบเจกต์ที่ระบุและตั้งค่าที่บ่งชี้ว่าล็อกถูกจับหรือไม่อย่างอะตอมิก.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Monitor](../)
* คลาส [TimeSpan](../../../system/timespan/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)