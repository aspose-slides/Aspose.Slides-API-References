---
title: VerifyData()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 209
url: /th/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) เมธอด

ตรวจสอบลายเซ็นของข้อมูล.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) เพื่อตรวจสอบลายเซ็นสำหรับ |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลายเซ็นที่ได้รับ |

### ค่าที่ส่งกลับ

True หากลายเซ็นถูกต้อง, false มิฉะนั้น.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุถูกต้อง

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายเซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมการแฮช. return true หากลายเซ็นถูกต้อง, มิฉะนั้น - false |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุถูกต้อง

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายเซ็น |
| offset | **int32_t** | ออฟเซ็ตใน **data** |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมการแฮช. return true หากลายเซ็นถูกต้อง, มิฉะนั้น - false |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุถูกต้อง

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | ข้อมูลที่ลงลายเซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมการแฮช. return true หากลายเซ็นถูกต้อง, มิฉะนั้น - false |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)