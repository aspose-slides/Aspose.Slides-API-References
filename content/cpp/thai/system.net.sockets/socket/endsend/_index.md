---
title: EndSend()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการส่งแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์.
type: docs
weight: 508
url: /th/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการส่งแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการส่งแบบอะซิงโครนัส |

### ค่าที่คืน

จำนวนไบต์ที่ส่ง.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) เมธอด

รอจนกว่าการส่งแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการส่งแบบอะซิงโครนัส |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ผลลัพธ์ที่ค่ารหัสข้อผิดพลาดจะถูกกำหนดเมื่อการส่งล้มเหลว |

### ค่าที่คืน

จำนวนไบต์ที่ส่ง.

## ดูเพิ่มเติม

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Socket](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)