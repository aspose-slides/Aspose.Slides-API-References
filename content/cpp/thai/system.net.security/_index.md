---
title: "System::Net::Security"
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: 
type: docs
weight: 716
url: /th/system.net.security/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | มีเมธอดสำหรับส่งข้อมูลประจุผ่านสตรีม วัตถุของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการตรวจสอบเสมอ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SslStream](./sslstream/) | สตรีมที่ใช้โปรโตคอล SSL เพื่อยืนยันตัวเซิร์ฟเวอร์และอาจยืนยันตัวไคลเอ็นต์ได้เช่นกัน |
## Enum

| Enum | คำอธิบาย |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | แฟล็กการตรวจสอบสิทธิ์ที่เฉพาะสำหรับ WebRequest |
| [SslPolicyErrors](./sslpolicyerrors/) | แสดงรายการข้อผิดพลาดของนโยบาย SSL |
| [EncryptionPolicy](./encryptionpolicy/) | แสดงรายการนโยบายการเข้ารหัส |
## Typedef

| Typedef | คำอธิบาย |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | ตัว delegate ของผู้ใช้ที่ใช้ตรวจสอบใบรับรอง SSL ระยะไกล |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | ตัว delegate ของผู้ใช้ที่ใช้เลือกใบรับรอง SSL ภายใน |