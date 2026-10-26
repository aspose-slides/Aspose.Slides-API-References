---
title: BeginGetHostEntry()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry-class ใหม่โดยใช้สตริงที่ระบุซึ่งมีชื่อโฮสต์หรือที่อยู่ IP
type: docs
weight: 105
url: /th/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry-class ใหม่โดยใช้สตริงที่ระบุซึ่งมีชื่อโฮสต์หรือที่อยู่ IP

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | สตริงที่มีชื่อโฮสต์หรือที่อยู่ IP |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้ซึ่งใช้เพื่อระบุการดำเนินการแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งคืน

วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อสร้างอินสแตนซ์ของคลาส IPHostEntry-class ใหม่โดยใช้ที่อยู่ IP ที่ระบุ

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | ที่อยู่ IP |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็คที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้ซึ่งใช้เพื่อระบุการดำเนินการแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่ส่งคืน

วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [Dns](../)
* คลาส [IPAddress](../../ipaddress/)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)