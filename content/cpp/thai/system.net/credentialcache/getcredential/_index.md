---
title: GetCredential()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนข้อมูลประจำตัวสำหรับคำนำหน้าของ URI และประเภทการตรวจสอบสิทธิ์ที่ระบุ.
type: docs
weight: 66
url: /th/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) วิธีการ


ส่งคืนข้อมูลประจำตัวสำหรับคำนำหน้าของ URI และประเภทการตรวจสอบสิทธิ์ที่ระบุ.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | คำนำหน้าของ URI. |
| authenticationType | [String](../../../system/string/) | ประเภทการตรวจสอบสิทธิ์. |

## CredentialCache::GetCredential(String, int32_t, String) วิธีการ


ส่งคืนข้อมูลประจำตัวสำหรับชื่อโฮสต์, พอร์ต และประเภทการตรวจสอบสิทธิ์ที่ระบุ.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ที่ข้อมูลประจำตัวเชื่อมโยง. |
| port | **int32_t** | หมายเลขพอร์ต. |
| authenticationType | [String](../../../system/string/) | ประเภทการตรวจสอบสิทธิ์. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)