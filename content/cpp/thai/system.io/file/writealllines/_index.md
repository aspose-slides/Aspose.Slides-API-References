---
title: WriteAllLines()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่แล้วและเขียนสตริงทั้งหมดจากคอลเลกชันที่สามารถวนซ้ำได้ตามที่ระบุลงในไฟล์โดยแต่ละสตริงอยู่บนบรรทัดใหม่โดยใช้การเข้ารหัสที่ระบุ
type: docs
weight: 456
url: /th/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) เมธอด

สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่แล้วและเขียนสตริงทั้งหมดจากคอลเลกชันที่สามารถวนซ้ำได้ตามที่กำหนดลงในไฟล์บนบรรทัดใหม่แต่ละบรรทัดโดยใช้การเข้ารหัสที่ระบุ

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | ไฟล์ที่จะสร้างหรือเขียนทับ |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | คอลเลกชันที่สามารถวนซ้ำได้ของสตริง |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) เมธอด

สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่แล้วและเขียนสตริงทั้งหมดจากอาร์เรย์สตริงที่กำหนดลงในไฟล์บนบรรทัดใหม่แต่ละบรรทัดโดยใช้การเข้ารหัสที่ระบุ

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | ไฟล์ที่จะสร้างหรือเขียนทับ |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | อาร์เรย์สตริง |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [File](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)