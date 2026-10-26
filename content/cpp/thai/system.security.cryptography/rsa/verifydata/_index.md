---
title: VerifyData()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุถูกต้องหรือไม่.
type: docs
weight: 157
url: /th/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่เซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริธึมแฮช |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติมเต็ม. คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลที่เซ็น |
| offset | **int32_t** | ออฟเซ็ตใน data |
| count | **int32_t** | จำนวนไบต์ที่จะทำแฮช |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริธึมแฮช |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติมเต็ม. คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุถูกต้องหรือไม่

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมที่เซ็น |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริธึมแฮช |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติมเต็ม. คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ดูเพิ่มเติม

* ประเภทนิยาม [ByteArrayPtr](../../../system/bytearrayptr/)
* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* ประเภทนิยาม [StreamPtr](../../../system/streamptr/)
* คลาส [RSASignaturePadding](../../rsasignaturepadding/)
* คลาส [RSA](../)
* โครงสร้าง [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)