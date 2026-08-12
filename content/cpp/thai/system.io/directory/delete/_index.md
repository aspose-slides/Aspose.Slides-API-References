---
title: Delete()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบไฟล์หรือไดเรกทอรีที่ระบุออก ไม่ขว้างข้อยกเว้น.
type: docs
weight: 14
url: /th/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) เมธอด


ลบไฟล์หรือไดเรกทอรีที่ระบุออก ไม่ขว้างข้อยกเว้น.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางไปยังไดเรกทอรีหรือไฟล์ที่ต้องการลบ |
| recursive | **bool** | หาก **path** ระบุไดเรกทอรีที่ไม่ว่างเปล่าแล้ว **recursive** จะกำหนดว่าความเนื้อหาทั้งหมดของไดเรกทอรีควรถูกลบแบบเรียกซ้ำหรือไม่; หากไดเรกทอรีที่ระบุโดย **path** ไม่ว่างเปล่าและ **recursive** มีค่าเป็น 'false' การดำเนินการจะล้มเหลว |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Directory](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)