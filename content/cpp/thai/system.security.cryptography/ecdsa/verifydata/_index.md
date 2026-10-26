---
title: VerifyData()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นลายเซ็นที่สมบูรณ์หรือไม่
type: docs
weight: 105
url: /th/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด


ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นลายเซ็นที่สมบูรณ์หรือไม่

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายเซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. คืนค่า true หากลายเซ็นถูกต้อง, หากไม่ใช่ - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด


ตรวจสอบว่ลายเซ็นของข้อมูลที่ระบุเป็นลายเซ็นที่สมบูรณ์หรือไม่

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายเซ็น |
| offset | **int32_t** | ตำแหน่งเริ่มต้นใน **data** |
| count | **int32_t** | จำนวนไบต์ที่ต้องทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. คืนค่า true หากลายเซ็นถูกต้อง, หากไม่ใช่ - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด


ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นลายเซ็นที่สมบูรณ์หรือไม่

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | ข้อมูลที่ลงลายเซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. คืนค่า true หากลายเซ็นถูกต้อง, หากไม่ใช่ - false. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* คลาส [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)