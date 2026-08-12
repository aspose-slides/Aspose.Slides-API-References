---
title: Create()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: สร้างไฟล์ใหม่ (หรือเขียนทับไฟล์ที่มีอยู่) และเปิดเพื่อการอ่านและการเขียนโดยใช้ขนาดบัฟเฟอร์และตัวเลือกที่ระบุ
type: docs
weight: 53
url: /th/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) เมธอด

สร้างไฟล์ใหม่ (หรือเขียนทับไฟล์ที่มีอยู่) และเปิดเพื่อการอ่านและการเขียนโดยใช้ขนาดบัฟเฟอร์และตัวเลือกที่ระบุ

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะสร้างหรือเขียนทับ |
| bufferSize | **int32_t** | จำนวนไบต์ที่บัฟเฟอร์เมื่ออ่านและเขียนไฟล์ |
| options | [FileOptions](../../fileoptions/) | ระบุวิธีการสร้างหรือเขียนทับไฟล์ |

### ค่าที่ส่งกลับ

ตัวชี้แบบ shared ไปยังอ็อบเจ็กต์ [FileStream](../../filestream/) ที่เกี่ยวข้องกับไฟล์ที่กำหนด

## ดูเพิ่มเติม

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)