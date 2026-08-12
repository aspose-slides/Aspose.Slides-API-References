---
title: WaitOne()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ล็อก semaphore. ทำการรอแบบไม่จำกัดหากจำเป็น.
type: docs
weight: 40
url: /th/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method

ล็อก semaphore. ทำการรอแบบไม่จำกัดหากจำเป็น.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### ค่าที่ส่งกลับ

จะคืนค่า true เสมอเนื่องจากไม่คืนค่าจนกว่า semaphore จะถูกล็อก.

## Semaphore::WaitOne(int) method

ล็อก semaphore. ทำการรอหากจำเป็น.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| millisecondsTimeout | int | ระยะเวลาการรอเป็นหน่วยมิลลิวินาที |

### ค่าที่ส่งกลับ

คืนค่า true หาก semaphore ถูกล็อก หรือ false หากเวลารอหมด.

## ดูเพิ่มเติม

* คลาส [Semaphore](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)