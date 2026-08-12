---
title: HashAlgorithmName
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "สตริงที่แสดงชื่อของอัลกอริทึมแฮช ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยอ้างอิง อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของประเภทนี้."
type: docs
weight: 755
url: /th/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) แสดงชื่อของอัลกอริทึมแฮช ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่า หรือโดยอ้างอิง อย่าใช้คลาส [System::SmartPtr](../../system/smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้.

```cpp
class HashAlgorithmName
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | สร้าง [HashAlgorithmName](./) จากค่า OID |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | รับ [HashAlgorithmName](./) ที่แสดง [MD5](../md5/) |
| [String](../../system/string/) [get_Name](./get_name/)() const | รับการแสดงผลเป็นสตริงของชื่ออัลกอริทึม |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | รับ [HashAlgorithmName](./) ที่แสดง [SHA1](../sha1/) |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | รับ [HashAlgorithmName](./) ที่แสดง [SHA256](../sha256/) |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | รับ [HashAlgorithmName](./) ที่แสดง [SHA384](../sha384/) |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | รับ [HashAlgorithmName](./) ที่แสดง [SHA512](../sha512/) |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | คอนสตรัคเตอร์ |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | รับการแสดงผลเป็นสตริงของชื่ออัลกอริทึม |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | พยายามสร้าง [HashAlgorithmName](./) จากค่า OID |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | ส่งคืนอ็อบเจกต์ [TypeInfo](../../system/typeinfo/) ที่แสดงโครงสร้าง [TimeSpan](../../system/timespan/) |

## ดูเพิ่มเติม

* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)