---
title: SignHash()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คำนวณลายเซ็นของค่าที่ระบุเป็นอินพุต
type: docs
weight: 196
url: /th/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method

คำนวณลายเซ็นของค่าที่ระบุเป็นอินพุต

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ค่าฮัชของข้อมูลที่ต้องทำลายเซ็น |
| str | const [String](../../../system/string/)\& | ตัวระบุอัลกอริทึมแฮชที่ใช้สร้างแฮช |

### ค่าที่ส่งคืน

[DSA](../../dsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)