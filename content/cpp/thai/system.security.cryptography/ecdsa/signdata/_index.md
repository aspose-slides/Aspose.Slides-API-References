---
title: SignData()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides for C++
description: คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและทำการเซ็นผลลัพธ์
type: docs
weight: 79
url: /th/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุ และทำการเซ็นผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลที่ได้รับ |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุ และทำการเซ็นผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า |
| offset | **int32_t** | ออฟเซ็ตในข้อมูล |
| count | **int32_t** | จำนวนไบต์ที่จะใช้เป็นข้อมูลเข้า |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลที่ได้รับ |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุ และทำการเซ็นผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลที่ได้รับ |

## ดูเพิ่มเติม

* การกำหนดชนิด [ByteArrayPtr](../../../system/bytearrayptr/)
* การกำหนดชนิด [StreamPtr](../../../system/streamptr/)
* คลาส [ECDsa](../)
* โครงสร้าง [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)