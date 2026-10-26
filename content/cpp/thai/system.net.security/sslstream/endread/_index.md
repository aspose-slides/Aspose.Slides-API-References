---
title: EndRead()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รอจนกว่าการดำเนินการอ่านแบบอะซิงโครนัสที่ระบุจะเสร็จสิ้น.
type: docs
weight: 430
url: /th/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) เมธอด

Waits until the specified asynchronous read operation completes.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่เป็นตัวแทนของการดำเนินการอ่านแบบอะซิงโครนัส |

### ค่าที่คืนกลับ

จำนวนไบต์ที่อ่านได้ในระหว่างการดำเนินการอ่านที่แสดงโดย **asyncResult**

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [SslStream](../)
* เนมส페ซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)