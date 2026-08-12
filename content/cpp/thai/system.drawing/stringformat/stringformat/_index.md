---
title: StringFormat()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส StringFormat.
type: docs
weight: 1
url: /th/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [StringFormat](../) ด้วยแฟลกรูปแบบที่ระบุและภาษา.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | การผสมแบบบิตของค่า enum StringFormatFlags ที่ระบุรูปแบบสตริงที่จะเป็นตัวแทนของอ็อบเจกต์ที่สร้าง |
| language | **int32_t** | ภาษาของข้อความ |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์สำเนา.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | อ็อบเจกต์ [StringFormat](../) ที่จะคัดลอกจาก |

## ดูเพิ่มเติม

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [StringFormat](../)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)