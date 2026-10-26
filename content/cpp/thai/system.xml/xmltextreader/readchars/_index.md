---
title: ReadChars()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: อ่านเนื้อหาข้อความขององค์ประกอบลงในบัฟเฟอร์อักขระ วิธีนี้ออกแบบมาเพื่ออ่านสตรีมข้อความที่ฝังอยู่ขนาดใหญ่โดยการเรียกใช้งานอย่างต่อเนื่อง.
type: docs
weight: 755
url: /th/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

อ่านเนื้อหาข้อความขององค์ประกอบลงในบัฟเฟอร์อักขระ วิธีนี้ออกแบบมาเพื่ออ่านสตรีมข้อความที่ฝังอยู่ขนาดใหญ่โดยการเรียกใช้งานอย่างต่อเนื่อง.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | อาเรย์ของอักขระที่ทำหน้าที่เป็นบัฟเฟอร์ที่เขียนเนื้อหาข้อความลงไป |
| index | **int32_t** | ตำแหน่งภายใน **buffer** ที่เมธอดสามารถเริ่มเขียนเนื้อหาข้อความได้ |
| count | **int32_t** | จำนวนอักขระที่ต้องเขียนลงใน **buffer** |

### ค่าที่ส่งคืน

จำนวนอักขระที่อ่านได้ ซึ่งอาจเป็น 0 หากตัวอ่านไม่ได้ตั้งอยู่บนองค์ประกอบหรือไม่มีเนื้อหาข้อความเหลือให้คืนค่าในบริบทปัจจุบัน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)