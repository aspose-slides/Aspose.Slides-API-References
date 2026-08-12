---
title: "System::Net::Cache"
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 664
url: /th/system.net.cache/
---
## คลาส

| Class | Description |
| --- | --- |
| [HttpRequestCachePolicy](./httprequestcachepolicy/) | นโยบายแคช HTTP ที่แสดงความหมายการแคชตาม RFC2616 วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อหุ้มคลาสนี้ไว้ในตัวชี้ [System::SmartPtr](../system/smartptr/) แล้วใช้ตัวชี้นี้ในการส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
| [RequestCachePolicy](./requestcachepolicy/) | นโยบายแคชคำขอทั่วไปที่ใช้สำหรับการแคชของ [Http](../system.net.http/), FTP ฯลฯ วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อหุ้มคลาสนี้ไว้ในตัวชี้ [System::SmartPtr](../system/smartptr/) แล้วใช้ตัวชี้นี้ในการส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |
## Enums

| Enum | Description |
| --- | --- |
| [RequestCacheLevel](./requestcachelevel/) | enum นี้อธิบายการตั้งค่าแคชที่ใช้ได้กับ [WebRequest](../system.net/webrequest/) ใดๆ |
| [HttpRequestCacheLevel](./httprequestcachelevel/) | enum นี้อธิบายการตั้งค่าแคชสำหรับ HTTP |
| [HttpCacheAgeControl](./httpcacheagecontrol/) | CacheAgeControl ใช้ในการระบุการตั้งค่าความต้องการเกี่ยวกับอายุและความสดของรายการที่แคช |