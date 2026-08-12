---
title: CheckPath()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าที่อยู่ที่ระบุเป็นที่อยู่ที่ถูกต้องหรือไม่โดยตรวจสอบว่ามีอักขระที่ไม่ถูกต้องหรือไม่ หากที่อยู่มีอักขระที่ไม่ถูกต้องจะมีข้อยกเว้นถูกโยน
type: docs
weight: 209
url: /th/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) เมธอด

กำหนดว่าที่อยู่ที่ระบุเป็นที่อยู่ที่ถูกต้องหรือไม่โดยตรวจสอบว่ามีอักขระที่ไม่ถูกต้องหรือไม่ หากที่อยู่มีอักขระที่ไม่ถูกต้องจะมีข้อยกเว้นถูกโยน

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางที่ต้องตรวจสอบ |
| msg | const [String](../../../system/string/)\& | ข้อความที่ส่งให้กับคอนสตรัคเตอร์ของอ็อบเจกต์ข้อยกเว้น |
| allow_empty | **bool** | ระบุว่าควรถือสตริงที่ว่างหรือเป็น null ว่าเป็นเส้นทางที่ถูกต้องหรือไม่ (true) หรือ (false); หากพารามิเตอร์นี้เป็น false และ **path** ว่างจะทิ้ง ArgumentException; หากพารามิเตอร์นี้เป็น false และ **path** เป็น null จะทิ้ง ArgumentNullException |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [Path](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)