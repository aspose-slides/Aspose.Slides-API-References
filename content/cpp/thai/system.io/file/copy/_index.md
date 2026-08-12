---
title: Copy()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คัดลอกไฟล์ที่ระบุไปยังตำแหน่งที่ระบุ หากไฟล์ปลายทางมีอยู่แล้ว พารามิเตอร์จะระบุว่าควรเขียนทับหรือไม่.
type: docs
weight: 40
url: /th/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) เมธอด

คัดลอกไฟล์ที่ระบุไปยังตำแหน่งที่ระบุ หากไฟล์ปลายทางมีอยู่แล้ว พารามิเตอร์จะระบุว่าควรเขียนทับหรือไม่.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | พาธของไฟล์ที่จะคัดลอก |
| destFileName | const [String](../../../system/string/)\& | พาธของตำแหน่งใหม่ของไฟล์ที่จะคัดลอก |
| overwrite | **bool** | จริง หากต้องการเขียนทับไฟล์ปลายทางที่มีอยู่แล้ว, เท็จ หากการคัดลอกควรล้มเหลวเมื่อไฟล์ปลายทางมีอยู่แล้ว |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [File](../)
* เนมส페ซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)