---
title: AppendAllLines()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มสตริงจากคอลเลกชันสตริงที่ระบุไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุโดยการเขียนแต่ละสตริงในบรรทัดใหม่ หากไฟล์ที่ระบุไม่มีอยู่ จะถูกสร้างขึ้น ไฟล์จะถูกปิดหลังจากเขียนสตริงทั้งหมดเสร็จสิ้น
type: docs
weight: 1
url: /th/system.io/file/appendalllines/
---
## File::AppendAllLines(const String&, const SharedPtr<Collections::Generic::IEnumerable<String>>, const EncodingPtr&) เมธอด

เพิ่มสตริงจากคอลเลกชันสตริงที่ระบุไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุ โดยเขียนแต่ละสตริงในบรรทัดใหม่ หากไฟล์ที่ระบุไม่มีอยู่ จะสร้างไฟล์ขึ้นใหม่ หลังจากเขียนสตริงทั้งหมดแล้ว ไฟล์จะถูกปิด

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะเพิ่มสตริงเข้าไป |
| contents | const [SharedPtr](../../../system/sharedptr/)<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)<[String](../../../system/string/)>>\& | สตริงที่เขียนลงในไฟล์ |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* คลาส [String](../../../system/string/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [File](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)