---
title: EndReceive()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รอจนกว่าการดำเนินการรับแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น.
type: docs
weight: 534
url: /th/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการรับแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการรับแบบอะซิงโครนัส |

### ค่าที่ส่งคืน

จำนวนไบต์ที่ได้รับ.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) เมธอด

รอจนกว่าการดำเนินการรับแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการรับแบบอะซิงโครนัส |
| errorCode | [SocketError](../../socketerror/)\& | พารามิเตอร์ output ที่จะได้รับค่าโค้ดข้อผิดพลาดเมื่อการดำเนินการรับล้มเหลว |

### ค่าที่ส่งคืน

จำนวนไบต์ที่ได้รับ.

## ดูเพิ่ม

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)