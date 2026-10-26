---
title: Enter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับล็อกแบบเอกสิทธิ์บนวัตถุที่ระบุ.
type: docs
weight: 1
url: /th/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) เมธอด


รับล็อกเฉพาะบนวัตถุที่ระบุ.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | วัตถุที่ใช้เพื่อรับล็อก monitor. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) เมธอด


รับล็อกเฉพาะบนวัตถุที่ระบุและตั้งค่าที่บ่งบอกว่าล็อกถูกจับไว้แบบอะตอมิก.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Monitor](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)