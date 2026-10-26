---
title: ReadLines()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านเนื้อหาของไฟล์ข้อความที่ระบุบรรทัดต่อบรรทัดโดยใช้การเข้ารหัสอักขระที่ระบุและคืนค่าคอลเลกชันที่เป็น enumerable ของสตริง ซึ่งแต่ละสตริงแทนบรรทัดเดียวของเนื้อหาไฟล์
type: docs
weight: 326
url: /th/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) เมธอด

อ่านเนื้อหาของไฟล์ข้อความที่ระบุบรรทัดต่อบรรทัดโดยใช้การเข้ารหัสอักขระที่กำหนดและคืนค่าคอลเลกชันที่เป็น enumerable ของสตริง ซึ่งแต่ละสตริงแทนบรรทัดเดียวของเนื้อหาไฟล์

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่ต้องการอ่าน |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่จะใช้ |

### Return Value

คอลเลกชันที่เป็น enumerable ของสตริงที่แสดงถึงเนื้อหาของไฟล์ที่ระบุ

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)