---
title: Read()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านข้อมูลจากสตรีม.
type: docs
weight: 14
url: /th/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านข้อมูลจากสตรีม.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | บัฟเฟอร์ข้อมูลปลายทาง. |
| offset | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ปลายทาง. |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่กำลังอ่านจริง ๆ.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) เมธอด

อ่านข้อมูลจากสตรีม.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | บัฟเฟอร์ข้อมูลปลายทาง. |
| offset | **int32_t** | ออฟเซ็ตในบัฟเฟอร์ปลายทาง. |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่กำลังอ่านจริง ๆ.

## ดูเพิ่มเติม

* ชนิดกำหนดเอง [ArrayPtr](../../../system/arrayptr/)
* คลาส [CryptoStream](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)