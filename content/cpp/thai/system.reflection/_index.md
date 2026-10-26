---
title: "System::Reflection"
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 755
url: /th/system.reflection/
---
## คลาส

| Class | Description |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) คลาสที่อธิบายแอสเซมบลี การสนับสนุนจำกัดเนื่องจากกฎต่างกันอย่างมากระหว่าง C# และ C++. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [AssemblyName](./assemblyname/) | กำหนดชื่อแอสเซมบลี วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton เพื่อลงทะเบียนประเภทในแอสเซมบลีที่กำลังทำงาน |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | ประเภทฐานสำหรับ singleton เพื่อลงทะเบียนประเภทในแอสเซมบลีที่กำลังทำงาน |
| [ConstructorInfo](./constructorinfo/) | ให้การเข้าถึงเมทาดาทาของคอนสตรัคเตอร์ |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException ถูกโยนโดยเมธอด Module.GetTypes หากคลาสใดในโมดูลไม่สามารถโหลดได้ ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ReflectionTypeLoadException แทน อย่าห่ออินสแตนซ์ของคลาส ReflectionTypeLoadException เข้าไปใน [System::SmartPtr](../system/smartptr/) |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException ถูกโยนโดยเมธอดที่เรียกผ่านการสะท้อน ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส TargetInvocationException แทน อย่าห่ออินสแตนซ์ของคลาส TargetInvocationException เข้าไปใน [System::SmartPtr](../system/smartptr/) |
| [FieldInfo](./fieldinfo/) | ค้นพบแอตทริบิวต์ของฟิลด์และให้การเข้าถึงเมทาดาทาของฟิลด์ |
| [MemberInfo](./memberinfo/) | ให้ข้อมูลการสะท้อนบนสมาชิก วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [MethodBase](./methodbase/) | ให้ข้อมูลพื้นฐานเกี่ยวกับเมธอด วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว เสมอห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [MethodInfo](./methodinfo/) | แสดงข้อมูลเกี่ยวกับเมธอดของคลาส |
| [PropertyInfo](./propertyinfo/) | แสดงข้อมูลของพร็อพเพอร์ตี้ |
## เอนัม

| Enum | Description |
| --- | --- |
| [BindingFlags](./bindingflags/) | กำหนดสมาชิกและโหมดการค้นหาและการผูกของประเภท |
| [FieldAttributes](./fieldattributes/) | แอตทริบิวต์ฟิลด์ที่สะท้อน |
| [MemberTypes](./membertypes/) | ทำเครื่องหมายแต่ละประเภทของสมาชิก |
## ประเภทนิยาม

| Typedef | Description |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException ถูกโยนโดยเมธอด Module.GetTypes หากคลาสใดในโมดูลไม่สามารถโหลดได้ อย่าห่ออินสแตนซ์ของคลาส ReflectionTypeLoadException เข้าไปใน [System::SmartPtr](../system/smartptr/) |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException ถูกโยนโดยเมธอดที่เรียกผ่านการสะท้อน อย่าห่ออินสแตนซ์ของคลาส TargetInvocationException เข้าไปใน [System::SmartPtr](../system/smartptr/) |