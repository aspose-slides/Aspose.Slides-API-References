---
title: "System::Collections::Specialized"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 391
url: /th/system.collections.specialized/
---
## คลาส

| Class | คำอธิบาย |
| --- | --- |
| [BitVector32](./bitvector32/) | ให้เวกเตอร์บิตขนาดเบาแบบง่ายพร้อมการเข้าถึงเป็นจำนวนเต็มหรือ [Boolean](../system/boolean/) อย่างง่ายต่อการจัดเก็บ 32 บิต. |
| [NameValueCollection](./namevaluecollection/) | คอลเลกชันของคีย์ [String](../system/string/) ที่เชื่อมโยงและค่าที่ [String](../system/string/) ที่สามารถเข้าถึงได้ทั้งโดยคีย์หรือโดยดัชนี. |
| [StringCollection](./stringcollection/) | รายการที่มีดัชนีของสตริง. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือการตรวจสอบความถูกต้อง. ให้ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอากูเมนต์. |
| [StringCollectionPtr](./stringcollectionptr/) | คอลเลกชันของสตริงแบบพอยน์เตอร์พร้อมตัวดำเนินการเข้าถึง. |
| [StringDictionary](./stringdictionary/) | [String](../system/string/) ไปยังพจนานุกรมสตริง. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือการตรวจสอบความถูกต้อง. ให้ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอากูเมนต์. |
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(**BitVector32::Section**, **BitVector32::Section**) | ตรวจสอบว่าวัตถุสองตัวที่ระบุเท่ากันหรือไม่. |
| **bool** [operator!=](./operator_not_equal/)(**BitVector32::Section**, **BitVector32::Section**) | ตรวจสอบว่าวัตถุสองตัวที่ระบุไม่เท่ากันหรือไม่. |