---
title: BeginSend()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เริ่มต้นการส่งข้อมูลแบบอะซิงโครนัส
type: docs
weight: 495
url: /th/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการส่งข้อมูลแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์สำหรับอ่านข้อมูลจาก |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุโดยเริ่มจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการส่ง |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการทำงานสำเร็จ |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้ไว้ใช้เพื่อระบุแต่ละการส่งแบบอะซิงโครนัสอย่างเป็นเอกลักษณ์ |

### ค่ารีเทิร์น

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการส่งแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* enum [SocketFlags](../../socketflags/)
* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [Socket](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)