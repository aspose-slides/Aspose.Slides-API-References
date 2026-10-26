---
title: EnumerateDirectories()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่กำหนด ทั้งในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากอยู่ในไดเรกทอรีที่ระบุ
type: docs
weight: 27
url: /th/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่กำหนด ทั้งในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากอยู่ในไดเรกทอรีที่ระบุ。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธเต็มหรือพาธสัมพันธ์ไปยังไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำเฉพาะในไดเรกทอรีที่ระบุหรือในโครงสร้างไดเรกทอรีทั้งหมดที่มีรากอยู่ในไดเรกทอรีที่ระบุ |

### ค่าที่ส่งกลับ

คอลเลกชันที่สามารถวนซ้ำได้ของพาธเต็มของไดเรกทอรีที่พบซึ่งชื่อตรงกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* คลาส [String](../../../system/string/)
* คลาส [Directory](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)