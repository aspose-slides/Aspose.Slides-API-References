---
title: IsBypassed()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าที่บ่งชี้ว่าควรไม่ใช้พร็อกซีสำหรับโฮสต์ที่ระบุ.
type: docs
weight: 40
url: /th/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) เมธอด


คืนค่าที่บ่งชี้ว่าควรไม่ใช้พร็อกซีสำหรับโฮสต์ที่ระบุ.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ของโฮสต์ที่ต้องตรวจสอบ. |

### ค่าที่คืนกลับ

True เมื่อไม่ควรใช้เซิร์ฟเวอร์พร็อกซี, มิฉะนั้นเป็น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [IWebProxy](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)