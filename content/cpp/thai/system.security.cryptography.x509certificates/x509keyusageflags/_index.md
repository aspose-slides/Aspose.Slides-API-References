---
title: X509KeyUsageFlags
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดวิธีที่คีย์ของใบรับรองสามารถใช้ได้.
type: docs
weight: 274
url: /th/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

กำหนดวิธีที่คีย์ของใบรับรองสามารถใช้ได้.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ไม่มีพารามิเตอร์การใช้คีย์ |
| EncipherOnly | 1 | คีย์สามารถใช้ได้เฉพาะการเข้ารหัส |
| CrlSign | 2 | คีย์สามารถใช้เซ็นรายการเพิกถอนใบรับรอง |
| KeyCertSign | 4 | คีย์สามารถใช้เซ็นใบรับรอง |
| KeyAgreement | 8 | คีย์สามารถใช้เพื่อกำหนดการทำข้อตกลงคีย์ |
| DataEncipherment | 16 | คีย์สามารถใช้สำหรับการเข้ารหัสข้อมูล |
| KeyEncipherment | 32 | คีย์สามารถใช้สำหรับการเข้ารหัสคีย์ |
| NonRepudiation | 64 | คีย์สามารถใช้สำหรับการตรวจสอบสิทธิ์ |
| DigitalSignature | 128 | คีย์สามารถใช้เป็นลายเซ็นดิจิทัล |
| DecipherOnly | 32768 | คีย์สามารถใช้ได้เฉพาะการถอดรหัส |

## ดูเพิ่มเติม

* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)