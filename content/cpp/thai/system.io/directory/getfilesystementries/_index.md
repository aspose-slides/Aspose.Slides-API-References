---
title: GetFileSystemEntries()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ
type: docs
weight: 92
url: /th/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) เมธอด

ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางเต็มหรือเส้นทางสัมพันธ์ไปยังไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาจะต้องทำเฉพาะในไดเรกทอรีที่ระบุเท่านั้น หรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ |

### ค่าที่คืนกลับ

อาเรย์ของเส้นทางเต็มของไฟล์และไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [Directory](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)