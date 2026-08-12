---
title: SignData()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คำนวณลายเซ็นของค่าตัวอินพุตที่ระบุ
type: docs
weight: 183
url: /th/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

คำนวณลายเซ็นของค่าตัวอินพุตที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลอินพุตจาก. |

### Return Value

[DSA](../../dsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

คำนวณลายเซ็นของค่าตัวอินพุตที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมเพื่ออ่านข้อมูลที่กำลังลงนามจาก. |

### Return Value

[DSA](../../dsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

คำนวณลายเซ็นของค่าตัวอินพุตที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลอินพุตจาก. |
| offset | **int32_t** | ดัชนีเริ่มต้นของสไลซ์บัฟเฟอร์อินพุต. |
| count | **int32_t** | ขนาดของสไลซ์บัฟเฟอร์อินพุต. |

### Return Value

[DSA](../../dsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุและลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลอินพุต. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม. ส่งคืนลายเซ็น [DSA](../../dsa/) สำหรับข้อมูลอินพุต. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุและลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | อาร์เรย์ข้อมูลอินพุต. |
| offset | **int32_t** | ออฟเซ็ตใน **data**. |
| count | **int32_t** | จำนวนไบต์ที่ใช้เป็นข้อมูลอินพุต. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม. ส่งคืนลายเซ็น [DSA](../../dsa/) สำหรับข้อมูลอินพุต. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้แฮชอัลกอริทึมที่ระบุและลงลายเซ็นผลลัพธ์

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมไบนารี. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | แฮชอัลกอริทึม. ส่งคืนลายเซ็น [DSA](../../dsa/) สำหรับข้อมูลอินพุต. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* คลาส [DSACryptoServiceProvider](../)
* คลาส [Stream](../../../system.io/stream/)
* โครงสร้าง [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)