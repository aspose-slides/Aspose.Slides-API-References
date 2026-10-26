---
title: SecurityPermissionFlag
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค่าสถานะของการอนุญาตความปลอดภัย.
type: docs
weight: 27
url: /th/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Flags of security permission.

```cpp
enum class SecurityPermissionFlag
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| NoFlags | 0 | ไม่มีการเข้าถึง. |
| Assertion | 1 | ยืนยันว่ามีการให้สิทธิ์. |
| UnmanagedCode | 2 | เรียกโค้ดที่ไม่ได้จัดการ. |
| SkipVerification | 4 | ข้ามการตรวจสอบโค้ด. |
| Execution | 8 | ดำเนินการโค้ด. |
| ControlThread | 16 | ดำเนินการกับเธรด. |
| ControlEvidence | 32 | ควบคุมหรือแก้ไขหลักฐาน CLR. |
| ControlPolicy | 64 | ดูและเปลี่ยนนโยบาย. |
| SerializationFormatter | 128 | ทำการซีรีไลซ์. |
| ControlDomainPolicy | 256 | ตั้งค่านโยบายโดเมน. |
| ControlPrincipal | 512 | ควบคุมวัตถุหลัก. |
| ControlAppDomain | 1024 | ควบคุมโดเมนของแอปพลิเคชัน. |
| RemotingConfiguration | 2048 | กำหนดค่ารีโมตติ้ง. |
| Infrastructure | 4096 | เชื่อมต่อไปยังโครงสร้างพื้นฐาน CLR. |
| BindingRedirects | 8192 | ดำเนินการเปลี่ยนเส้นทางการผูกมัดโดยเจตนา. |
| AllFlags | 16383 | ไม่มีข้อจำกัด. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Security::Permissions](../)
* ไลบรารี [Aspose.Slides](../../)