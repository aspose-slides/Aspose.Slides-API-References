---
title: ConformanceLevel
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ระบุระดับการตรวจสอบข้อมูลเข้าและข้อมูลออกที่วัตถุ XmlReader และ XmlWriter ทำ
type: docs
weight: 625
url: /th/system.xml/conformancelevel/
---
## ConformanceLevel enum

ระบุระดับการตรวจสอบข้อมูลเข้าและข้อมูลออกที่วัตถุ [XmlReader](../xmlreader/) และ [XmlWriter](../xmlwriter/) ทำ

```cpp
enum class ConformanceLevel
```

### ค่า

| ชื่อ | ค่า | รายละเอียด |
| --- | --- | --- |
| Auto | 0 | วัตถุ [XmlReader](../xmlreader/) หรือ [XmlWriter](../xmlwriter/) จะตรวจจับโดยอัตโนมัติว่าควรทำการตรวจสอบระดับเอกสารหรือระดับส่วนย่อย และทำการตรวจสอบที่เหมาะสม หากคุณห่อหุ้มวัตถุ [XmlReader](../xmlreader/) หรือ [XmlWriter](../xmlwriter/) อีกชั้นหนึ่ง วัตถุภายนอกจะไม่ทำการตรวจสอบความสอดคล้องเพิ่มเติม การตรวจสอบความสอดคล้องจะถูกมอบหมายให้กับวัตถุพื้นฐาน |
| Fragment | 1 | ข้อมูล XML เป็น [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) ตามที่ W3C กำหนด ระดับความสอดคล้องนี้แทนเอกสาร XML ที่อาจไม่มีองค์ประกอบรากแต่จัดรูปแบบได้อย่างถูกต้อง ระดับการตรวจสอบนี้รับประกันว่าการสตรีมที่อ่านหรือเขียนสามารถใช้ได้กับตัวประมวลผลใดก็ได้เป็น [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) |
| Document | 2 | ข้อมูล XML สอดคล้องกับกฎของ [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) ที่จัดรูปแบบถูกต้องตามที่ W3C กำหนด ระดับการตรวจสอบนี้รับประกันว่าการสตรีมที่อ่านหรือเขียนสามารถใช้ได้กับตัวประมวลผลใดก็ได้เป็น [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)