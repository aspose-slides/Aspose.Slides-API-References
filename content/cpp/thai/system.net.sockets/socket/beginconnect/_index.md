---
title: BeginConnect()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส.
type: docs
weight: 573
url: /th/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) method


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | จุดเชื่อมต่อระยะไกล |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการทำงานเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการเชื่อมต่อแบบอะซิงโครนัสอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการทำงานเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการเชื่อมต่อแบบอะซิงโครนัสอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการทำงานเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการเชื่อมต่อแบบอะซิงโครนัสอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | ที่อยู่ IP ของโฮสต์ระยะไกล |
| port | **int32_t** | หมายเลขพอร์ตของโฮสต์ระยะไกล |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการทำงานเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุแต่ละการเชื่อมต่อแบบอะซิงโครนัสอย่างไม่ซ้ำกัน |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่ม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [EndPoint](../../../system.net/endpoint/)
* คลาส [Object](../../../system/object/)
* คลาส [Socket](../)
* คลาส [String](../../../system/string/)
* คลาส [IPAddress](../../../system.net/ipaddress/)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)