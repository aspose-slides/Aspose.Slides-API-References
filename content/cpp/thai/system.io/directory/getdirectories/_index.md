---
title: GetDirectories()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่ระบุนั้นหรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มต้นจากไดเรกทอรีที่ระบุ
type: docs
weight: 66
url: /th/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) เมธอด

ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มต้นจากไดเรกทอรีที่ระบุ

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธเต็มหรือพาธสัมพัทธ์ของไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไดเรกทอรีที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาจะทำเฉพาะในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มต้นจากไดเรกทอรีที่ระบุ |

### ค่าที่ส่งคืน

อาร์เรย์ของพาธเต็มของไดเรกทอรีที่พบซึ่งชื่อสอดคล้องกับ **searchPattern**

## ดูเพิ่มเติม

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)