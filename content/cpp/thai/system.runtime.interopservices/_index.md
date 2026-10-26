---
title: "System::Runtime::InteropServices"
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 781
url: /th/system.runtime.interopservices/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Details_ExternalException](./details_externalexception/) | ประเภทข้อยกเว้นพื้นฐานสำหรับข้อยกเว้น COM interop ทั้งหมดและข้อยกเว้นการจัดการข้อยกเว้นแบบโครงสร้าง (SEH) ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ExternalException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส ExternalException เข้าไปใน [System::SmartPtr](../system/smartptr/). |
| [Marshal](./marshal/) | ให้การดำเนินการ marshalling สำหรับความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีโค้ดที่จัดการบนฝั่ง C++ นี่เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ |
| [MemoryMarshal](./memorymarshal/) | ให้การดำเนินการ memory marshalling สำหรับความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีโค้ดที่จัดการบนฝั่ง C++ นี่เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ |
| [NativeLibrary](./nativelibrary/) |  |
| [OSPlatform](./osplatform/) |  |

## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [FILETIME](./filetime/) | เก็บส่วนประกอบของเวลาไฟล์ ประเภทนี้ควรจัดสรรบนสแตกและส่งให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](../system/smartptr/) เพื่อจัดการออบเจ็กต์ของประเภทนี้ |
| [RuntimeInformation](./runtimeinformation/) |  |

## Enums

| Enum | คำอธิบาย |
| --- | --- |
| [GCHandleType](./gchandletype/) | กำหนดวิธีที่ handle ถูกจัดการโดย garbage collector |
| [VarEnum](./varenum/) | กำหนดวิธีที่สมาชิกของ array ควรทำการ marshalled |

## Typedefs

| Typedef | คำอธิบาย |
| --- | --- |
| [ExternalException](./externalexception/) |  |