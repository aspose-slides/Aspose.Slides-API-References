---
title: GetCredential()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนข้อมูลประจำตัวสำหรับ URI ที่ระบุและประเภทการรับรองความถูกต้อง.
type: docs
weight: 92
url: /th/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) เมธอด

ส่งคืนข้อมูลประจำตัวสำหรับ URI ที่ระบุและประเภทการรับรองความถูกต้อง.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | ประเภทการรับรองความถูกต้อง. |

## NetworkCredential::GetCredential(String, int32_t, String) เมธอด

ส่งคืนข้อมูลประจำตัวสำหรับชื่อโฮสต์ พอร์ต และประเภทการรับรองความถูกต้องที่ระบุ.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | [String](../../../system/string/) | ชื่อโฮสต์. |
| port | **int32_t** | หมายเลขพอร์ต. |
| authenticationType | [String](../../../system/string/) | ประเภทการรับรองความถูกต้อง. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [NetworkCredential](../)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)