---
title: EndRead()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์.
type: docs
weight: 261
url: /th/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) เมธอด

รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการอ่านแบบอะซิงโครนัส |

### ค่าที่ส่งคืน

จำนวนไบต์ที่อ่านได้ระหว่างการดำเนินการอ่านที่แสดงโดย **asyncResult**

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [NetworkStream](../)
* เนมสเปซ [System::Net::Sockets](../../)
* ไลบรารี [Aspose.Slides](../../../)