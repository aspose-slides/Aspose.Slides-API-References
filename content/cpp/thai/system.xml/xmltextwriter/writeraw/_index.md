---
title: WriteRaw()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เขียนมาร์กอัปดิบด้วยตนเองจากบัฟเฟอร์อักขระ.
type: docs
weight: 417
url: /th/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) เมธอด

เขียนมาร์กอัปดิบด้วยตนเองจากบัฟเฟอร์อักขระ

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | อาเรย์อักขระที่มีข้อความที่ต้องเขียน |
| index | **int32_t** | ตำแหน่งในบัฟเฟอร์ที่บ่งบอกจุดเริ่มต้นของข้อความที่ต้องเขียน |
| count | **int32_t** | จำนวนอักขระที่ต้องเขียน |

## XmlTextWriter::WriteRaw(const String\&) เมธอด

เขียนมาร์กอัปดิบด้วยตนเองจากสตริง

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) ที่มีข้อความที่ต้องเขียน |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlTextWriter](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)