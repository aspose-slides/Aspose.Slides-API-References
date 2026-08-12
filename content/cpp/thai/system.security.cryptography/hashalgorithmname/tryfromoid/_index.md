---
title: TryFromOid()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: พยายามสร้าง HashAlgorithmName จากค่า OID.
type: docs
weight: 66
url: /th/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) เมธอด

Try to create [HashAlgorithmName](../) from OID-value.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID value. |
| value | [HashAlgorithmName](../)\& | Output [HashAlgorithmName](../). |

### ค่าที่คืน

true หาก OID ที่ระบุเป็นอัลกอริทึมแฮชที่ถูกต้อง มิฉะนั้น - false.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* โครงสร้าง [HashAlgorithmName](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)