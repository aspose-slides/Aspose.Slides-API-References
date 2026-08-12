---
title: SignData()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คำนวณค่าฮาชของอาเรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุ และทำการลงลายเซ็นผลลัพธ์
type: docs
weight: 131
url: /th/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

คำนวณค่าแฮชของอาเรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุและทำการลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาเรย์ข้อมูล |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติม. คืนค่า [RSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

คำนวณค่าแฮชของอาเรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุและทำการลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาเรย์ข้อมูล |
| offset | **int32_t** | ออฟเซ็ตใน **data** |
| count | **int32_t** | จำนวนไบต์ที่จะใช้เป็นข้อมูลอินพุต |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติม. คืนค่า [RSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) เมธอด

คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุและทำการลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | โหมดการเติม. คืนค่า [RSA](../) ลายเซ็นสำหรับข้อมูลอินพุต |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* คลาส [RSASignaturePadding](../../rsasignaturepadding/)
* คลาส [RSA](../)
* โครงสร้าง [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)