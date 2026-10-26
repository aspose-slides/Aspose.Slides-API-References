---
title: Seek()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าตำแหน่งของสตรีมที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน
type: docs
weight: 209
url: /th/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) เมธอด


ตั้งค่าตำแหน่งของสตรีมที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| offset | **int64_t** | ออฟเซ็ตเป็นจำนวนไบต์ซึ่งสัมพันธ์กับตำแหน่งที่ระบุโดย **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | ระบุตำแหน่งที่ออฟเซ็ตจะคำนวณจากและทิศทางที่ออฟเซ็ตจะถูกคำนวณไป. |

### ค่าที่คืน

ตำแหน่งใหม่ของสตรีม

## ดูเพิ่มเติม

* Enum [SeekOrigin](../../seekorigin/)
* คลาส [FileStream](../)
* เนมสเปซ [System::IO](../../)
* Library [Aspose.Slides](../../../)