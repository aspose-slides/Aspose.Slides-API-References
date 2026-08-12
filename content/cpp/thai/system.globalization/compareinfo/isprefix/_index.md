---
title: IsPrefix()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่า string ที่ระบุเริ่มต้นด้วย prefix ที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่ระบุ
type: docs
weight: 105
url: /th/system.globalization/compareinfo/isprefix/
---
## CompareInfo::IsPrefix(const String\&, const String\&, CompareOptions) const method


ตรวจสอบว่า string ที่ระบุเริ่มต้นด้วย prefix ที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่ระบุ

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix, CompareOptions options) const
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | สตริงต้นทาง |
| prefix | const [String](../../../system/string/)\& | สตริง prefix |
| options | [CompareOptions](../../compareoptions/) | ตัวเลือกการเปรียบเทียบ |

### ค่าที่คืนกลับ

True if string starts with prefix; otherwise false.

## CompareInfo::IsPrefix(const String\&, const String\&) const method


ตรวจสอบว่า string ที่ระบุเริ่มต้นด้วย prefix ที่ระบุ

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix) const
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | สตริงต้นทาง |
| prefix | const [String](../../../system/string/)\& | สตริง prefix |

### ค่าที่คืนกลับ

True if string starts with prefix; otherwise false.

## ดูเพิ่มเติม

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)