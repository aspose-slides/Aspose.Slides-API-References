---
title: BeginAcceptTcpClient()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มต้นการดำเนินการยอมรับแบบอะซิงโครนัส
type: docs
weight: 170
url: /th/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มต้นการดำเนินการยอมรับแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้กำหนดเพื่อระบุเอกลักษณ์ของแต่ละการเชื่อมต่อแบบอะซิงโครนัส |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการยอมรับแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* กำหนดประเภท [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [TcpListener](../)
* เนมสเปส [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)