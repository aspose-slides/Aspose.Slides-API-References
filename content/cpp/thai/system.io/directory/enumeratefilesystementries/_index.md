---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ.
type: docs
weight: 53
url: /th/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) เมธอด

ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางเต็มหรือเส้นทางสัมพันธ์ไปยังไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์และไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำเฉพาะในไดเรกทอรีที่ระบุหรือในโครงสร้างไดเรกทอรีทั้งหมดที่มีรากจากไดเรกทอรีที่ระบุ |

### ค่าที่ส่งกลับ

คอลเลคชันที่สามารถวนซ้ำได้ของเส้นทางเต็มของไฟล์และไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)