---
title: CreateHttp()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของคลาส WebRequest โดยใช้ URI ที่ระบุ
type: docs
weight: 79
url: /th/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) เมธอด


สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../) โดยใช้ URI ที่ระบุ

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | URI ที่ใช้เพื่อสร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../) |

### ค่าที่ส่งกลับ

อินสแตนซ์ของคลาส WebRequest ที่สร้างใหม่
## หมายเหตุ



จะเกิดข้อยกเว้น NotSupportedException เมื่อ URI ที่ระบุขึ้นต้นด้วยสคีมใด ๆ ยกเว้น [http://](http://) หรือ [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) เมธอด


สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../) โดยใช้ URI ที่ระบุ

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่ใช้เพื่อสร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../) |

### ค่าที่ส่งกลับ

อินสแตนซ์ของคลาส WebRequest ที่สร้างใหม่
## หมายเหตุ



จะเกิดข้อยกเว้น NotSupportedException เมื่อ URI ที่ระบุขึ้นต้นด้วยสคีมใด ๆ ยกเว้น [http://](http://) หรือ [https://](https://). 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [HttpWebRequest](../../httpwebrequest/)
* คลาส [String](../../../system/string/)
* คลาส [WebRequest](../)
* คลาส [Uri](../../../system/uri/)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)