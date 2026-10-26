---
title: "System::Net::Http"
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: 
type: docs
weight: 677
url: /th/system.net.http/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | แสดงถึงเนื้อหา HTTP เป็นอาเรย์ของไบต์. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [Details_HttpRequestException](./details_httprequestexception/) | คลาสข้อยกเว้นพื้นฐานถูกโยนโดยคลาส [HttpClient](./httpclient/) และ [HttpMessageHandler](./httpmessagehandler/). อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส HttpRequestException แทน. อย่าห่ออินสแตนซ์ของคลาส HttpRequestException เข้าไปใน [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | แสดงถึงคลาสฐานของไคลเอนต์ HTTP สำหรับส่งคำขอและรับการตอบกลับ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpClientHandler](./httpclienthandler/) | แสดงถึงตัวจัดการข้อความเริ่มต้นที่ใช้โดยคลาส [HttpClient](./httpclient/). วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpContent](./httpcontent/) | แสดงถึงเนื้อหาของเอนทิตี้ HTTP. [Object](../system/object/) ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpMessageHandler](./httpmessagehandler/) | แสดงถึงประเภทฐานสำหรับตัวจัดการข้อความ HTTP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpMessageInvoker](./httpmessageinvoker/) | อนุญาตให้แอปพลิเคชันเรียกเมธอด Send บนโซ่ตัวจัดการ HTTP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpMethod](./httpmethod/) | แสดงถึงเมธอด HTTP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpRequestMessage](./httprequestmessage/) | แสดงถึงข้อความร้องขอ HTTP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpResponseMessage](./httpresponsemessage/) | แสดงถึงข้อความตอบกลับ HTTP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสตนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [HttpUtilities](./httputilities/) | มีเมธอดอรรถประโยชน์. |
| [StringContent](./stringcontent/) | แสดงถึงเนื้อหา HTTP เป็นสตริง. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือด้วย operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |

## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## Enum

| Enum | คำอธิบาย |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | ระบุว่าเมื่อใดควรทำงาน [HttpClient](./httpclient/) ให้เสร็จสมบูรณ์. |
| [HttpParseResult](./httpparseresult/) | ระบุผลลัพธ์ของการพาร์ส. |

## Typedef

| Typedef | คำอธิบาย |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |