---
title: SignData()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุและทำการเซ็นผลลัพธ์
type: docs
weight: 79
url: /th/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและทำการเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลอินพุต |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืน [DSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและทำการเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลอินพุต |
| offset | **int32_t** | ออฟเซ็ตใน **data** |
| count | **int32_t** | จำนวนไบต์ที่ใช้เป็นข้อมูลอินพุต |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืน [DSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) เมธอด

คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและทำการเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช ส่งคืน [DSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* คลาส [DSA](../)
* โครงสร้าง [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)