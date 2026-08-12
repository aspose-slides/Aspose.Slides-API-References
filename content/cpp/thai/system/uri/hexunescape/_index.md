---
title: HexUnescape()
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: แปลงการแสดงผลเลขฐานสิบหกของอักขระที่ระบุให้เป็นอักขระ
type: docs
weight: 443
url: /th/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) method

แปลงการแสดงผลเลขฐานสิบหกของอักขระที่ระบุให้เป็นอักขระ

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | สตริงที่ประกอบด้วยการแสดงผลเลขฐานสิบหกของอักขระ |
| index | **int32_t**\& | ตำแหน่งใน **pattern** ที่การแสดงผลเลขฐานสิบหกของอักขระเริ่มต้น |

### ค่าที่คืน

อักขระที่แสดงผลเป็นเลขฐานสิบหกที่ตำแหน่ง **index**. หากอักขระที่ตำแหน่ง **index** ไม่ได้เข้ารหัสเป็นเลขฐานสิบหก จะคืนอักขระที่ตำแหน่ง **index**. ค่าของ **index** จะถูกเพิ่มขึ้นเพื่อชี้ไปที่อักขระถัดจากอักขระที่คืนค่า

## ดูเพิ่มเติม

* คลาส [String](../../string/)
* คลาส [Uri](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)