---
title: GetCookieHeader()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่า HTTP header ที่มีคุกกี้ที่เกี่ยวข้องกับ URI ที่ระบุ
type: docs
weight: 170
url: /th/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) เมธอด


คืนค่า HTTP header ที่มีคุกกี้ที่เกี่ยวข้องกับ URI ที่ระบุ

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่จะนำไปสร้างชื่อ header |

### ค่าที่ส่งกลับ

HTTP header ที่มีคุกกี้ที่เกี่ยวข้องกับ URI ที่ระบุ

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) เมธอด


คืนค่า HTTP header ที่มีคุกกี้ที่เกี่ยวข้องกับ URI ที่ระบุ

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่จะนำไปสร้างชื่อ header |
| optCookie2 | [String](../../../system/string/)\& | พารามิเตอร์ผลลัพธ์ที่คุกกี้ที่รองรับเวอร์ชันสูงสุดจะถูกกำหนดค่าให้ |

### ค่าที่ส่งกลับ

 HTTP header ที่มีคุกกี้ที่เกี่ยวข้องกับ URI ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Uri](../../../system/uri/)
* Class [CookieContainer](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)