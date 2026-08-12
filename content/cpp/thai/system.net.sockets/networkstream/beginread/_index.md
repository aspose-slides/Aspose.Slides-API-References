---
title: BeginRead()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มการดำเนินการอ่านแบบอะซิงโครนัส
type: docs
weight: 248
url: /th/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ไบต์ที่บรรจุไบต์ที่อ่านได้จะถูกเขียนลง |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะอ่าน |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้ซึ่งใช้เพื่อระบุตัวปฏิบัติการอ่านแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการอ่านแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [NetworkStream](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)