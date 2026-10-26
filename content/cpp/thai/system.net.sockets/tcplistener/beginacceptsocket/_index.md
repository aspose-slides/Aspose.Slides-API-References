---
title: BeginAcceptSocket()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เริ่มต้นการทำงานรับแบบอะซิงโครนัส
type: docs
weight: 144
url: /th/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มต้นการทำงานรับแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คำเรียกกลับที่จะถูกเรียกเมื่อการทำงานเสร็จสมบูรณ์ |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดเตรียมเพื่อระบุการเชื่อมต่อแบบอะซิงโครนัสแต่ละรายการอย่างเฉพาะเจาะจง |

### ค่าที่ส่งคืน

วัตถุ [IAsyncResult](../../../system/iasyncresult/) แทนการทำงานรับแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [TcpListener](../)
* เนมสเปซ [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)