---
title: GetNamespace()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงคืน namespace ของการทดสอบที่ระบุ.
type: docs
weight: 14
url: /th/system/testtoolsext/getnamespace/
---
## TestToolsExt::GetNamespace(const char *, const char *, std::string\&) เมธอด


ดึงคืน namespace ของการทดสอบที่ระบุ.

```cpp
static bool System::TestToolsExt::GetNamespace(const char *class_name, const char *method_name, std::string &name_space)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| class_name | const char * | คลาสที่ต้องการค้นหา. |
| method_name | const char * | เมธอดที่ต้องการค้นหา. |
| name_space | std::string\& | ตัวแปรเพื่อใส่ชื่อ namespace เข้าไป, หากพบ. |

### ค่าที่ส่งคืน

true หากพบเมธอดการทดสอบ, false ในกรณีอื่น.

## ดูเพิ่มเติม

* Struct [TestToolsExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)