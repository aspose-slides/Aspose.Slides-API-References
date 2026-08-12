---
title: VerifyData()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้องหรือไม่
type: docs
weight: 92
url: /th/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงนาม |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช คืนค่า true หากลายเซ็นถูกต้อง, ไม่เช่นนั้น - false |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงนาม |
| offset | **int32_t** | ออฟเซ็ตใน **data** |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช คืนค่า true หากลายเซ็นถูกต้อง, ไม่เช่นนั้น - false |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของสตรีมไบต์ที่ระบุเป็นที่ถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | ข้อมูลที่ลงนาม |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช คืนค่า true หากลายเซ็นถูกต้อง, ไม่เช่นนั้น - false |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)