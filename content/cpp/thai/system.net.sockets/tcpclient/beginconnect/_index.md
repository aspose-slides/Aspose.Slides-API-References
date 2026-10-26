---
title: BeginConnect()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส.
type: docs
weight: 261
url: /th/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ระยะไกล |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุการดำเนินการเชื่อมต่อแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) แทนการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุการดำเนินการเชื่อมต่อแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) แทนการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | พอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุการดำเนินการเชื่อมต่อแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IAsyncResult](../../../system/iasyncresult/) แทนการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [TcpClient](../)
* คลาส [IPAddress](../../../system.net/ipaddress/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)