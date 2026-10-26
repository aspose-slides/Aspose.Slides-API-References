---
title: EndGetResponse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รอจนกว่าการร้องขอแบบอะซิงโครนัสที่ระบุสำหรับทรัพยากรจะเสร็จสิ้น.
type: docs
weight: 287
url: /th/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) เมธอด


รอจนกว่าการร้องขอแบบอะซิงโครนัสที่ระบุสำหรับทรัพยากรจะเสร็จสิ้น.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร |

### ค่าที่ส่งกลับ

การตอบสนองเว็บ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [WebResponse](../../webresponse/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [WebRequest](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)