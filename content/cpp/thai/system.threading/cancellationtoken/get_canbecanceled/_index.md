---
title: get_CanBeCanceled()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่าตัวโทเค็นนี้สามารถอยู่ในสถานะยกเลิกได้หรือไม่
type: docs
weight: 27
url: /th/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const เมธอด

ตรวจสอบว่าตัวโทเค็นนี้สามารถอยู่ในสถานะยกเลิกได้หรือไม่

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```

### ค่าที่คืนค่า

true หากตัวโทเค็นนี้สามารถอยู่ในสถานะยกเลิกได้; มิฉะนั้น false.

## หมายเหตุ

โทเค็นที่สร้างจาก [CancellationTokenSource](../../cancellationtokensource/) จะคืนค่า true, ในขณะที่โทเค็น None จะคืนค่า false เสมอ.

## ดูเพิ่มเติม

* คลาส [CancellationToken](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)