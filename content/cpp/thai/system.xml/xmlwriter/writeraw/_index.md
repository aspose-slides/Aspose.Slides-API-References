---
title: WriteRaw()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อถูกแทนที่ในคลาสที่สืบทอด จะเขียนมาร์กอัปแบบดิบด้วยตนเองจากบัฟเฟอร์อักขระ.
type: docs
weight: 287
url: /th/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) method


เมื่อถูกแทนที่ในคลาสที่สืบทอด จะเขียนมาร์กอัปแบบดิบด้วยตนเองจากบัฟเฟอร์อักขระ.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | อาเรย์ของอักขระที่มีข้อความที่ต้องการเขียน. |
| index | **int32_t** | ตำแหน่งภายในบัฟเฟอร์ที่ระบุดจุดเริ่มต้นของข้อความที่ต้องการเขียน. |
| count | **int32_t** | จำนวนอักขระที่ต้องการเขียน. |

## XmlWriter::WriteRaw(const String\&) method


เมื่อถูกแทนที่ในคลาสที่สืบทอด จะเขียนมาร์กอัปแบบดิบด้วยตนเองจากสตริง.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) ที่มีข้อความที่ต้องการเขียน. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlWriter](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)