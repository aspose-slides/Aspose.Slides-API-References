---
title: IDocumentProperties
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคุณสมบัติของงานนำเสนอ
type: docs
weight: 5730
url: /th/aspose.slides/idocumentproperties/
---
## IDocumentProperties อินเทอร์เฟซ

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | คืนค่า หรือกำหนดผู้เขียนของงานนำเสนอ. อ่าน/เขียน String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | คืนค่า หรือกำหนดประเภทของงานนำเสนอ. อ่าน/เขียน String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | คืนค่า หรือกำหนดความคิดเห็นของงานนำเสนอ. อ่าน/เขียน String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | คืนค่า หรือกำหนดสถานะเนื้อหาของงานนำเสนอ. อ่าน/เขียน String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | คืนค่า หรือกำหนดประเภทเนื้อหาของงานนำเสนอ. อ่าน/เขียน String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | คืนค่าจำนวนของคุณสมบัติที่กำหนดเองที่มีอยู่ในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | คืนค่าวันที่ที่งานนำเสนอถูกสร้าง. ค่าเป็นเวลา UTC. อ่าน/เขียน DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | บ่งบอกการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | ระบุจำนวนสไลด์ที่ซ่อนไว้ในเอกสารงานนำเสนอ. อ่านอย่างเดียว Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. อ่าน/เขียน String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตในส่วนนี้เท่านั้น. ผู้ผลิตคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติที่กำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | คืนค่า หรือกำหนดคำสำคัญของงานนำเสนอ. อ่าน/เขียน String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | คืนค่าวันที่ที่งานนำเสนอถูกพิมพ์ครั้งล่าสุด. อ่าน/เขียน DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขงานนำเสนอ. อ่าน/เขียน String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | คืนค่าวันที่ที่งานนำเสนอถูกแก้ไขครั้งสุดท้าย. ค่าเป็นเวลา UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในกระบวนการบันทึกวัตถุ IPresentation). สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่ส่งคืนโดยเมธอด [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) กรุณาดูตัวอย่างในสรุปเมธอด [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | บ่งบอกว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์ได้รับการอัปเดต. ตั้งค่าส่วนนี้เป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติผู้จัดการ. อ่าน/เขียน String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ระบุจำนวนรวมของคลิปเสียงหรือวิดีโอที่มีอยู่ในเอกสาร. อ่านอย่างเดียว Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ระบุจำนวนสไลด์ในงานนำเสนอที่มีโน้ต. อ่านอย่างเดียว Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | ระบุจำนวนรวมของย่อหน้าที่พบในเอกสารถ้ามี. อ่านอย่างเดียว Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | คืนค่า หรือกำหนดรูปแบบที่ต้องการของงานนำเสนอ. อ่าน/เขียน String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | คืนค่า หรือกำหนดหมายเลขฉบับแก้ไขของงานนำเสนอ. อ่าน/เขียน Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | บ่งบอกโหมดการแสดงผลของภาพย่อเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดใช้งานการปรับขนาดภาพย่อให้พอดีกับหน้าจอ. ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดใช้งานการครอบภาพย่อเพื่อแสดงเฉพาะส่วนที่พอดีกับหน้าจอ. อ่าน/เขียน Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | กำหนดว่าการนำเสนอนี้ถูกแชร์ระหว่างคนหลายคนหรือไม่. อ่าน/เขียน Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | ระบุจำนวนรวมของสไลด์ในเอกสารงานนำเสนอ. อ่านอย่างเดียว Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | คืนค่า หรือกำหนดหัวข้อของงานนำเสนอ. อ่าน/เขียน String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของงานนำเสนอ. อ่าน/เขียน String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | ระบุชื่อของแต่ละส่วนเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสาร แต่เป็นการแทนความคิดของส่วนต่าง ๆ ของเอกสาร. อ่านอย่างเดียว string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | เวลาการแก้ไขรวมของงานนำเสนอ. อ่าน/เขียน TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ระบุจำนวนรวมของคำที่มีในเอกสาร. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | ล้างและตั้งค่าตั้งต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | ลบคุณสมบัติที่กำหนดเองทั้งหมด. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | ตรวจสอบการมีอยู่ของคุณสมบัติที่กำหนดเองที่มีชื่อระบุ. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | คืนชื่อคุณสมบัติที่กำหนดเองที่ดัชนีระบุ. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | ดึงค่าบูลีนชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | ดึงค่าที่เป็น DateTime ชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | ดึงค่าที่เป็น double ชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | ดึงค่าที่เป็น float ชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | ดึงค่าที่เป็น integer ชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | ดึงค่าที่เป็น string ชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | ดึงอาเรย์ของป้ายความอ่อนไหวจากคุณสมบัติเอกสารที่กำหนดเอง (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | ลบคุณสมบัติที่กำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ตั้งค่าคุณสมบัติบูลีนที่กำหนดเองตามชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ตั้งค่าคุณสมบัติ DateTime ที่กำหนดเองตามชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ตั้งค่าคุณสมบัติ double ที่กำหนดเองตามชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ตั้งค่าคุณสมบัติ float ที่กำหนดเองตามชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ตั้งค่าคุณสมบัติ integer ที่กำหนดเองตามชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ตั้งค่าคุณสมบัติ string ที่กำหนดเองตามชื่อ. |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* ชุดประกอบ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->