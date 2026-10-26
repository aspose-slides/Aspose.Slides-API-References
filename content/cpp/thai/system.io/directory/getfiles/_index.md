---
title: GetFiles()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ค้นหาไฟล์ที่ตรงกับเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะอยู่ในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่ระบุ.
type: docs
weight: 79
url: /th/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) method


ค้นหาไฟล์ที่ตรงกับเกณฑ์การค้นหาที่ระบุไม่ว่าจะอยู่ในไดเรกทอรีที่ระบุหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่ระบุ

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | พาธเต็มหรือพาธสัมพันธ์ไปยังไดเรกทอรีที่ต้องการค้นหา |
| searchPattern | const [String](../../../system/string/)\& | รูปแบบชื่อของไฟล์ที่ต้องการค้นหา |
| searchOption | [SearchOption](../../searchoption/) | ระบุว่าการค้นหาต้องทำในไดเรกทอรีที่ระบุเท่านั้นหรือในต้นไม้ไดเรกทอรีทั้งหมดที่มีรากเป็นไดเรกทอรีที่ระบุ |

### Return Value

อาเรย์ของพาธเต็มของไฟล์ที่พบซึ่งชื่อตรงกับ **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)