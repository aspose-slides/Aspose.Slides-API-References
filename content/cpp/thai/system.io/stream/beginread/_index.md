---
title: BeginRead()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส.
type: docs
weight: 157
url: /th/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) เมธอด

Initiates an asynchronous read operation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | **buffer** ที่ใช้เพื่อการอ่าน |
| offset | int | ออฟเซ็ตที่เริ่มจากศูนย์ใน **buffer** ระบุตำแหน่งที่เริ่มเขียนข้อมูลที่อ่าน |
| count | int | จำนวนไบต์ที่จะอ่าน |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการทำงานเสร็จสมบูรณ์ |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการอ่านแบบอะซิงโครนัสโดยเฉพาะ |

### ค่าที่คืนกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการอ่านแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [Stream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)