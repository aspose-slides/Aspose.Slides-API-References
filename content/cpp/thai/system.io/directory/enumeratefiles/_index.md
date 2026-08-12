---
title: EnumerateFiles()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่ระบุหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่ระบุ
type: docs
weight: 40
url: /th/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) เมธอด

ค้นหาไฟล์ที่ตรงตามเงื่อนไขการค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่กำหนดหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่ระบุ

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางเต็มหรือเส้นทางสัมพันธ์ของไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาจะทำเฉพาะในไดเรกทอรีที่ระบุหรือในโครงสร้างไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีที่ระบุ |

### ค่าที่ส่งคืน

คอลเลกชันที่สามารถวนซ้ำได้ของเส้นทางเต็มของไฟล์ที่พบซึ่งชื่อสอดคล้องกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* คลาส [String](../../../system/string/)
* คลาส [Directory](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)