---
title: RegisterPrefix()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ลงทะเบียนรุ่นสืบทอด WebRequest สำหรับ URI ที่ระบุ.
type: docs
weight: 92
url: /th/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr<IWebRequestCreate>) เมธอด


ลงทะเบียนรุ่นสืบทอด [WebRequest](../) สำหรับ URI ที่ระบุ.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI หรือคำนำหน้า URI |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../) |

### ค่าที่ส่งกลับ

เป็น true เมื่อรุ่นสืบทอด [WebRequest](../) ถูกลงทะเบียนสำเร็จสำหรับ URI ที่ระบุ, มิฉะนั้นเป็น false.

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [IWebRequestCreate](../../iwebrequestcreate/)
* คลาส [WebRequest](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)