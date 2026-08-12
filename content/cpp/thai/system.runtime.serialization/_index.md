---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 794
url: /th/system.runtime.serialization/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | เป็นการดำเนินการพื้นฐานของอินเทอร์เฟซ [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) |
| [IFormatterConverter](./iformatterconverter/) | ให้การเชื่อมต่อระหว่างอินสแตนซ์ของ [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) กับคลาสที่จัดเตรียมโดยตัวจัดรูปแบบซึ่งเหมาะสมที่สุดในการแยกข้อมูลภายใน [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) |
| [ISerializable](./iserializable/) | อินเทอร์เฟซของอ็อบเจ็กต์ที่สามารถทำการซีเรียลไลซ์ได้. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [SerializationInfo](./serializationinfo/) | เก็บชุดของฟิลด์ที่มีชื่อซึ่งแทนอ็อบเจ็กต์ที่ถูกซีเรียลไลซ์. ไม่ได้ทำการใช้งาน. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [StreamingContext](./streamingcontext/) | คลาสจำลองเพื่อให้คลาสที่แปลโดยใช้ StreamingContext สามารถคอมไพล์ได้. ไม่ควรจัดการอินสแตนซ์ของคลาสนี้โดย [SmartPtr](../system/smartptr/), พวกมันต้องได้รับการจัดสรรบนสแตกเท่านั้น. |
## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [SerializationException](./serializationexception/) |  |