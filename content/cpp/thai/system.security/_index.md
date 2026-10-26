---
title: "System::Security"
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: 
type: docs
weight: 807
url: /th/system.security/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Secure string, แสดงข้อความที่ควรเก็บเป็นความลับ. คลาสนี้ไม่ได้เข้ารหัสข้อมูลภายใน. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการเคลียร์ข้อกำหนด. ควรห่อคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์. |
| [SecureStringMarshal](./securestringmarshal/) | คอลเลกชันของเมธอดสำหรับจัดสรรและคัดลอกบล็อกหน่วยความจำที่ไม่ได้จัดการ. |
| [SecurityElement](./securityelement/) | โมเดลวัตถุ XML สำหรับการเข้ารหัสวัตถุความปลอดภัย. ยังไม่ได้ทำงาน. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการเคลียร์ข้อกำหนด. ควรห่อคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์. |

## นิยามชนิด

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) ประเภทพอยน์เตอร์. |