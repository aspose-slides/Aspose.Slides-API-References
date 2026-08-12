---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบข้อมูลรับรองเครือข่ายสำหรับคำนำหน้า URI และประเภทการรับรองที่ระบุ
type: docs
weight: 53
url: /th/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) เมธอด


ลบข้อมูลรับรองเครือข่ายสำหรับคำนำหน้า URI และประเภทการรับรองที่ระบุ

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | คำนำหน้า URI |
| authenticationType | [String](../../../system/string/) | ประเภทการรับรอง |

## CredentialCache::Remove(String, int32_t, String) เมธอด


ลบข้อมูลรับรองเครือข่ายสำหรับชื่อโฮสต์ พอร์ต และประเภทการรับรองที่ระบุ

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ที่เชื่อมโยงกับข้อมูลรับรอง |
| port | **int32_t** | หมายเลขพอร์ต |
| authenticationType | [String](../../../system/string/) | ประเภทการรับรอง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)