---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุวิธีการจัดการค่าที่เป็นเวลาเมื่อแปลงระหว่างสตริงและ DateTime.
type: docs
weight: 781
url: /th/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

ระบุวิธีการจัดการค่าที่เป็นเวลาเมื่อแปลงระหว่างสตริงและ [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Values

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Local | 0 | ถือว่าเป็นเวลาในเครื่องท้องถิ่น หากวัตถุ [DateTime](../../system/datetime/) แทนเวลาสากลที่ประสานงาน (UTC) จะถูกแปลงเป็นเวลาในเครื่องท้องถิ่น. |
| Utc | 1 | ถือว่าเป็นเวลามาตรฐาน UTC หากวัตถุ [DateTime](../../system/datetime/) แทนเวลาท้องถิ่น จะถูกแปลงเป็น UTC. |
| Unspecified | 2 | ถือว่าเป็นเวลาในเครื่องท้องถิ่น หาก [DateTime](../../system/datetime/) ถูกแปลงเป็นสตริง หากสตริงถูกแปลงเป็น [DateTime](../../system/datetime/) ให้แปลงเป็นเวลาในเครื่องท้องถิ่นหากระบุเขตเวลา. |
| RoundtripKind | 3 | ข้อมูลเขตเวลาควรได้รับการรักษาไว้เมื่อต้องแปลง. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)