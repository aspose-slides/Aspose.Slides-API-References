---
title: "System::Web::Services::Protocols"
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 1080
url: /th/system.web.services.protocols/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | แสดงข้อยกเว้นที่ถูกโยนเมื่อเรียกเมธอดผ่าน SOAP และเกิดข้อผิดพลาด ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ให้ใช้ SoapException class แทน ไม่ควรห่ออินสแตนซ์ของ SoapException class เข้าไปใน [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | คลาสฐานนี้ใช้ในทุกพร็อกซีไคลเอนต์บริการ XML [Web](../system.web/) ที่ใช้ HTTP วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | อินสแตนซ์ของคลาสนี้จะถูกส่งต่อเป็นอาร์กิวเมนต์ให้กับตัวมอบหมาย InvokeCompletedEventHandler วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapClientMessage](./soapclientmessage/) | แสดงข้อมูลในคำร้องขอ SOAP ที่ส่งหรือการตอบรับ SOAP ที่ได้รับ วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | ระบุว่าข้อความ SOAP ทั้งหมดที่ส่งหรือถูกคืนค่าจากเมธอดใช้การจัดรูปแบบ Document วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | กำหนดรูปแบบเริ่มต้นสำหรับคำร้องขอและการตอบรับ SOAP วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapHeader](./soapheader/) | แสดงเนื้อหาของส่วนหัว SOAP วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapHeaderAttribute](./soapheaderattribute/) | ระบุส่วนหัว SOAP ที่เมธอดบริการ XML [Web](../system.web/) หรือไคลเอนต์บริการ XML [Web](../system.web/) สามารถประมวลผลได้ วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapHeaderCollection](./soapheadercollection/) | มีการรวบรวมชุดของอินสแตนซ์ของคลาส [SoapHeader](./soapheader/) |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | เซอร์วิสพร็อกซีไคลเอนต์ต้องสืบทอดคลาสนี้เมื่อใช้ SOAP วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [SoapMessage](./soapmessage/) | แสดงข้อความ SOAP วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |
| [WebClientProtocol](./webclientprotocol/) | คลาสฐานนี้ใช้ในทุกพร็อกซีไคลเอนต์บริการ XML [Web](../system.web/) ที่สร้างด้วย ASP.NET วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งของการตรวจสอบ เสมอ ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน |

## ชนิดกำหนดค่า

| ชนิดกำหนดค่า | คำอธิบาย |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | ระบุทิศทางของส่วนหัว SOAP |
| [SoapMessageStage](./soapmessagestage/) | ระบุขั้นตอนการประมวลผลของข้อความ SOAP |
| [SoapParameterStyle](./soapparameterstyle/) | ระบุรูปแบบของพารามิเตอร์ในข้อความ SOAP |
| [SoapProtocolVersion](./soapprotocolversion/) | ระบุเวอร์ชันของ SOAP |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | ระบุตัวเลือกของวิธีที่ข้อความ SOAP ถูกกำหนดเส้นทางไปยังบริการ XML [Web](../system.web/) |

## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [SoapException](./soapexception/) |  |