---
title: EndRead()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์.
type: docs
weight: 183
url: /th/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) เมธอด

Waits until the specified asynchronous read operation completes.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) อ็อบเจกต์ที่เป็นตัวแทนของการดำเนินการอ่านแบบอะซิงโครนัส |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่านระหว่างการดำเนินการอ่านที่แสดงโดย **asyncResult**

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Stream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)