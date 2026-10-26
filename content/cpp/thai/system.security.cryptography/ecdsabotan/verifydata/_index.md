---
title: VerifyData()
second_title: เอกสารอ้างอิง API Aspose.Slides สำหรับ C++
description: ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง
type: docs
weight: 170
url: /th/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) เมธอด

ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นที่ถูกต้อง

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | ข้อมูลที่ลงลายมือชื่อ |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช; คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)