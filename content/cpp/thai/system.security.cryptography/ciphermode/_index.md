---
title: CipherMode
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: โหมดการเข้ารหัสบล็อก.
type: docs
weight: 885
url: /th/system.security.cryptography/ciphermode/
---
## CipherMode enum

โหมดการเข้ารหัสบล็อก.

```cpp
enum class CipherMode
```

### ค่า

| ชื่อ | ค่า | รายละเอียด |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining ที่รวมบล็อกปัจจุบันกับบล็อกก่อนหน้าเพื่อปรับปรุงการเข้ารหัส. |
| ECB | 2 | โหมด electronic codebook ที่ไม่มีผลกระทบระหว่างบล็อก; ทำให้การเข้ารหัสอ่อนแอลง. |
| OFB | 3 | โหมด output feedback ที่จัดการบล็อกอินพุตขนาดใหญ่เป็นชิ้นเล็ก ๆ. |
| CFB | 4 | โหมด cipher feedback ที่จัดการบล็อกอินพุตขนาดใหญ่เป็นชิ้นเล็ก ๆ. กฎการจัดรูปแตกต่างจาก OFB. |
| CTS | 5 | โหมด cipher text stealing ทำงานคล้าย CBC ยกเว้นสองบล็อกสุดท้ายของข้อความ. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)