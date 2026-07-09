---
title: IDocumentProperties
second_title: Aspose.Sildes สำหรับอ้างอิง API ของ .NET
description: แสดงคุณสมบัติของการนำเสนอ.
type: docs
weight: 5710
url: /th/aspose.slides/idocumentproperties/
---
## IDocumentProperties อินเทอร์เฟซ

แสดงคุณสมบัติของการนำเสนอ

```csharp
public interface IDocumentProperties
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | คืนหรือกำหนดค่าแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | คืนค่าเวอร์ชันของแอปพลิเคชัน. อ่านอย่างเดียว String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | คืนหรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | คืนหรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | คืนหรือกำหนดคำอธิบายของการนำเสนอ. อ่าน/เขียน String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | คืนหรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | คืนหรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | คืนหรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | คืนจำนวนคุณสมบัติที่กำหนดเองที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | คืนวันที่การนำเสนอถูกสร้าง. ค่าอยู่ในรูปแบบ UTC. อ่าน/เขียน DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | บ่งบอกการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | คืนหรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. อ่าน/เขียน String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตโดยเฉพาะในส่วนนี้. ผู้ผลิตต่อไปที่เปิดเอกสารนี้จะอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | คืนหรือกำหนดคุณสมบัติที่กำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. อ่าน/เขียน Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | คืนหรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | คืนวันที่การนำเสนอถูกพิมพ์ครั้งล่าสุด. อ่าน/เขียน DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | คืนหรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอเป็นคนสุดท้าย. อ่าน/เขียน String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | คืนวันที่การนำเสนอถูกแก้ไขล่าสุด. ค่าอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ IPresentation). สามารถเปลี่ยนได้ผ่านอินสแตนซ์ DocumentProperties ที่ส่งกลับโดยเมธอด [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) โปรดดูตัวอย่างในสรุปเมธอด [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | บ่งบอกว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์ถูกอัปเดต. ตั้งค่าส่วนนี้เป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | คืนหรือกำหนดคุณสมบัติผู้จัดการ. อ่าน/เขียน String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ระบุจำนวนรวมของคลิปเสียงหรือวิดีโอที่มีอยู่ในเอกสาร. อ่านอย่างเดียว Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | คืนหรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ระบุจำนวนสไลด์ในการนำเสนอที่มีโน้ต. อ่านอย่างเดียว Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | ระบุจำนวนรวมของย่อหน้าที่พบในเอกสาร (หากมี). อ่านอย่างเดียว Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | คืนหรือกำหนดรูปแบบที่ต้องการของการนำเสนอ. อ่าน/เขียน String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | คืนหรือกำหนดหมายเลขรุ่นของการนำเสนอ. อ่าน/เขียน Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | บ่งบอกโหมดการแสดงผลของภาพย่อเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดใช้การปรับขนาดของภาพย่อให้พอดีกับการแสดงผล. ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดใช้การครอบภาพย่อให้แสดงเฉพาะส่วนที่พอดีกับการแสดงผล. อ่าน/เขียน Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | ระบุจำนวนรวมของสไลด์ในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | คืนหรือกำหนดหัวข้อของการนำเสนอ. อ่าน/เขียน String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | คืนหรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | ระบุชื่อของแต่ละส่วนของเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนเชิงแนวคิดของส่วนเอกสาร. อ่านอย่างเดียว string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | เวลาแก้ไขรวมของการนำเสนอ. อ่าน/เขียน TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ระบุจำนวนคำรวมที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | ล้างและตั้งค่าตัวเริ่มต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | ลบคุณสมบัติที่กำหนดเองทั้งหมด. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | ตรวจสอบการมีอยู่ของคุณสมบัติที่กำหนดเองที่มีชื่อระบุ. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | คืนชื่อคุณสมบัติที่กำหนดเองที่ตำแหน่งที่ระบุ. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | รับค่า boolean ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | รับค่า DateTime ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | รับค่า double ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | รับค่า float ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | รับค่า integer ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | รับค่า string ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | รับอาร์เรย์ของป้ายความอ่อนไหวจากคุณสมบัติเอกสารที่กำหนดเอง (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | ลบคุณสมบัติที่กำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ตั้งค่าคุณสมบัติ boolean ที่กำหนดเองที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ตั้งค่าคุณสมบัติ DateTime ที่กำหนดเองที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ตั้งค่าคุณสมบัติ double ที่กำหนดเองที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ตั้งค่าคุณสมบัติ float ที่กำหนดเองที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ตั้งค่าคุณสมบัติ integer ที่กำหนดเองที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ตั้งค่าคุณสมบัติ string ที่กำหนดเองที่มีชื่อ. |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->