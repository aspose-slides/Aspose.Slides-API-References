---
title: Semaphore()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้าง semaphore ที่ไม่มีชื่อ.
type: docs
weight: 1
url: /th/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) คอนสตรัคเตอร์

สร้าง semaphore ที่ไม่มีชื่อ.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| initialCount | int | จำนวนเริ่มต้นของรายการที่ทำงานอยู่ |
| maximumCount | int | จำนวนรายการที่อนุญาตสูงสุด |

## Semaphore::Semaphore(int, int, const String\&) คอนสตรัคเตอร์

สร้าง semaphore ที่มีชื่อ.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| initialCount | int | จำนวนเริ่มต้นของรายการที่ทำงานอยู่ |
| maximumCount | int | จำนวนรายการที่อนุญาตสูงสุด |
| name | const [String](../../../system/string/)\& | [Semaphore](../) ชื่อ |

## Semaphore::Semaphore(int, int, const String\&, bool\&) คอนสตรัคเตอร์

สร้าง semaphore ที่มีชื่อ.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| initialCount | int | จำนวนเริ่มต้นของรายการที่ทำงานอยู่ |
| maximumCount | int | จำนวนรายการที่อนุญาตสูงสุด |
| name | const [String](../../../system/string/)\& | [Semaphore](../) ชื่อ |
| createdNew | **bool**\& | อ้างอิงไปยังตัวแปรที่ตั้งค่าเป็น true หาก semaphore ถูกสร้างและเป็น false หากใช้ semaphore ที่มีชื่อเดียวกันที่มีอยู่แล้ว |

## ดูเพิ่มเติม

* คลาส [Semaphore](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)