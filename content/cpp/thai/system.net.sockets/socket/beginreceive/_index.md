---
title: BeginReceive()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส
type: docs
weight: 521
url: /th/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) วิธีการ

เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่ข้อมูลที่รับจะถูกกำหนด |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ในอาร์เรย์ที่ระบุโดยเริ่มจากพารามิเตอร์ 'offset' |
| socketFlags | [SocketFlags](../../socketflags/) | พฤติกรรมการรับ |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่ถูกเรียกเมื่อการดำเนินการสำเร็จ |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุอย่างเอกลักษณ์แต่ละการรับแบบอะซิงโครนัส |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการรับแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)