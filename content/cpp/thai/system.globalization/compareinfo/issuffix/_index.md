---
title: IsSuffix()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่าสตริงที่ระบุลงท้ายด้วย suffix ที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่ระบุ
type: docs
weight: 118
url: /th/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const method


ตรวจสอบว่าสตริงที่ระบุลงท้ายด้วย suffix ที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่ระบุ

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | สตริงต้นฉบับ |
| suffix | const [String](../../../system/string/)\& | สตริง suffix |
| options | [CompareOptions](../../compareoptions/) | ตัวเลือกการเปรียบเทียบ |

### Return Value

True หากสตริงลงท้ายด้วย suffix; มิฉะนั้น false.

## CompareInfo::IsSuffix(const String\&, const String\&) const method


ตรวจสอบว่าสตริงที่ระบุลงท้ายด้วย suffix ที่ระบุ

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | สตริงต้นฉบับ |
| suffix | const [String](../../../system/string/)\& | สตริง suffix |

### Return Value

True หากสตริงลงท้ายด้วย suffix; มิฉะนั้น false.

## See Also

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)