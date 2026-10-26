---
title: VerifySetDefaults()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบและตั้งค่าค่าเริ่มต้นของแอตทริบิวต์
type: docs
weight: 482
url: /th/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) เมธอด

ตรวจสอบและตั้งค่าคุณลักษณะเริ่มต้นของแอตทริบิวต์

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | ข้อกำหนดของคุกกี้ |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | อ็อบเจกต์ของคลาส Uri ที่ใช้เพื่อเริ่มต้นฟิลด์ภายใน |
| isLocalDomain | **bool** | ค่าที่ระบุว่าคุกกี้ถูกผลักเข้าสู่โดเมนท้องถิ่นหรือไม่ |
| localDomain | [String](../../../system/string/) | ชื่อโดเมนท้องถิ่น |
| setDefault | **bool** | ค่าที่ระบุว่าคุณลักษณะของคุกกี้ต้องถูกเริ่มต้นด้วยค่าเริ่มต้นหรือไม่ |
| shouldThrow | **bool** | ค่าที่ระบุว่าควรทำการโยนข้อยกเว้นเมื่อค่าที่ระบุไม่ถูกต้องหรือไม่ |

### ค่าผลลัพธ์

เป็น true เมื่อค่าทั้งหมดถูกต้อง, มิฉะนั้นเป็น false.

## ดูเพิ่มเติม

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)