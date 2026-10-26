---
title: SignData()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุและทำการลงนามผลลัพธ์
type: docs
weight: 131
url: /th/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) เมธอด


คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุและทำการลงนามผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) เมธอด


คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุและทำการลงนามผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า. |
| offset | **int32_t** | ออฟเซ็ตใน **data**. |
| count | **int32_t** | จำนวนไบต์ที่จะใช้เป็นข้อมูลเข้า. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ECDsaBotan::SignData(const StreamPtr\&) เมธอด


คำนวณค่าแฮชของสตรีมไบนารีที่ระบุและทำการลงนามผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) เมธอด


คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่กำหนดและทำการลงนามผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) เมธอด


คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่กำหนดและทำการลงนามผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลเข้า. |
| offset | **int32_t** | ออฟเซ็ตใน **data**. |
| count | **int32_t** | จำนวนไบต์ที่จะใช้เป็นข้อมูลเข้า. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) เมธอด


คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้อัลกอริทึมแฮชที่กำหนดและทำการลงนามผลลัพธ์

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### อากิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช. ส่งคืนลายเซ็น ECDSA สำหรับข้อมูลเข้า. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* คลาส [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)