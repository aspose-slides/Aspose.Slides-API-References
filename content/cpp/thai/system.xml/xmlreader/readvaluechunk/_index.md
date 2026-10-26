---
title: ReadValueChunk()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ่านสตรีมข้อความขนาดใหญ่ที่ฝังอยู่ในเอกสาร XML.
type: docs
weight: 807
url: /th/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) เมธอด


อ่านสตรีมข้อความขนาดใหญ่ที่ฝังอยู่ในเอกสาร XML

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | อาเรย์ของอักขระที่ทำหน้าที่เป็นบัฟเฟอร์เพื่อเขียนเนื้อหาข้อความลงไป ค่าตัวนี้ไม่สามารถเป็น **nullptr**. |
| index | **int32_t** | ค่าออฟเซ็ตภายในบัเฟอร์ที่ [XmlReader](../) สามารถเริ่มคัดลอกผลลัพธ์ได้. |
| count | **int32_t** | จำนวนอักขระสูงสุดที่จะคัดลอกเข้าไปในบัเฟอร์ จำนวนอักขระจริงที่คัดลอกจะถูกส่งกลับจากเมธอดนี้. |

### Return Value

จำนวนอักขระที่อ่านเข้าไปในบัเฟอร์ ค่า 0 จะถูกส่งกลับเมื่อไม่มีเนื้อหาข้อความเพิ่มเติม

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)