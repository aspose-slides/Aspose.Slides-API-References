---
title: "System::Xml::Serialization"
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: 
type: docs
weight: 1158
url: /th/system.xml.serialization/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [IXmlSerializable](./ixmlserializable/) | ให้การจัดรูปแบบที่กำหนดเองสำหรับการทำให้เป็น XML และการทำให้เป็น XML อีกครั้ง วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบค่าความถูกต้อง เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [XmlAttributeOverrides](./xmlattributeoverrides/) | อนุญาตให้แทนที่แอตทริบิวต์เมื่อใช้ [XmlSerializer](./xmlserializer/) เพื่อทำการซีเรียลไลซ์หรือดีซีเรียลไลซ์วัตถุ วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นั้นเพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [XmlRootAttribute](./xmlrootattribute/) | ทำเครื่องหมายเป้าหมายแอตทริบิวต์เป็นองค์ประกอบรากของ XML และควบคุมการทำให้เป็น XML ของมัน วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [XmlSerializationReader](./xmlserializationreader/) | คลาสบริการที่ปรับปรุงประสบการณ์ของ [XmlReader](../system.xml/xmlreader/) |
| [XmlSerializationWriter](./xmlserializationwriter/) | คลาสบริการที่ปรับปรุงประสบการณ์ของ [XmlWriter](../system.xml/xmlwriter/) |
| [XmlSerializer](./xmlserializer/) | ทำการซีเรียลไลซ์และดีซีเรียลไลซ์วัตถุเป็นและจากเอกสาร XML วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [XmlSerializerImplementation](./xmlserializerimplementation/) | คลาสภายในสำหรับใช้ร่วมกับ [XmlSerializer](./xmlserializer/) |
| [XmlSerializerNamespaces](./xmlserializernamespaces/) | มีเนมสเปซและพรีฟิกซ์ XML ที่ [Serialization::XmlSerializer](./xmlserializer/) ใช้เพื่อสร้างชื่อที่ผ่านการกำหนดคุณลักษณะในอินสแตนซ์เอกสาร XML |