---
title: "System::StringExtra"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 911
url: /th/system.stringextra/
---
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | ต่อเชื่อมอาร์เรย์ของสตริง. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | ต่อเชื่อมสตริง. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | ต่อเชื่อมสตริง. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | ต่อเชื่อมสตริง. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | แปลงหลายวัตถุเป็นสตริงและต่อเชื่อมสตริงที่ได้. การจำเพาะสำหรับประเภท [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | แปลงหลายวัตถุเป็นสตริงและต่อเชื่อมสตริงที่ได้. การจำเพาะสำหรับประเภทเลขคณิต. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | แปลงหลายวัตถุเป็นสตริงและต่อเชื่อมสตริงที่ได้. การจำเพาะสำหรับโครงสร้างและประเภทค่าประเภทอื่นๆ. |