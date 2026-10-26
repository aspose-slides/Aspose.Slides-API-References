---
title: SignData()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คำนวณลายเซ็นของค่าตัวรับเข้าที่ระบุ
type: docs
weight: 183
url: /th/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) เมธอด


คำนวณลายเซ็นของค่าตัวรับเข้าที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลอินพุตจาก |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | แฮชอัลกอริทึมที่ใช้ |

### ค่าที่ส่งกลับ

[RSA](../../rsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) เมธอด


คำนวณลายเซ็นของค่าตัวรับเข้าที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream เพื่ออ่านข้อมูลที่กำลังลงลายเซ็นจาก |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | แฮชอัลกอริทึมที่ใช้ |

### ค่าที่ส่งกลับ

[RSA](../../rsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) เมธอด


คำนวณลายเซ็นของค่าตัวรับเข้าที่ระบุ

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) เพื่ออ่านข้อมูลอินพุตจาก |
| offset | **int32_t** | ดัชนีเริ่มต้นของส่วนย่อยบัฟเฟอร์อินพุต |
| count | **int32_t** | ขนาดของส่วนย่อยบัฟเฟอร์อินพุต |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | แฮชอัลกอริทึมที่ใช้ |

### ค่าที่ส่งกลับ

[RSA](../../rsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [RSACryptoServiceProvider](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)