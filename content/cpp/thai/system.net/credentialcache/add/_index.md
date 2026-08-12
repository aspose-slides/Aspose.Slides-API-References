---
title: Add()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มข้อมูลรับรองเครือข่ายที่ระบุลงในแคช
type: docs
weight: 40
url: /th/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) เมธอด


เพิ่มข้อมูลรับรองเครือข่ายที่ระบุลงในแคช

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | คำนำหน้าของ URI ของแหล่งข้อมูลซึ่งข้อมูลรับรองเชื่อมโยงด้วย |
| authenticationType | [String](../../../system/string/) | รูปแบบการตรวจสอบสิทธิ์ |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | ข้อมูลรับรองที่จะเพิ่ม |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) เมธอด


เพิ่มข้อมูลรับรองเครือข่ายที่ระบุลงในแคช

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์ที่ข้อมูลรับรองเชื่อมโยงด้วย |
| port | **int32_t** | หมายเลขพอร์ต |
| authenticationType | [String](../../../system/string/) | รูปแบบการตรวจสอบสิทธิ์ |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | ข้อมูลรับรองที่จะเพิ่ม |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [NetworkCredential](../../networkcredential/)
* คลาส [CredentialCache](../)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)