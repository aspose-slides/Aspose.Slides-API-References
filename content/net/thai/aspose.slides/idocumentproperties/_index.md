---
title: IDocumentProperties
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคุณสมบัติของการนำเสนอ.
type: docs
weight: 5710
url: /th/aspose.slides/idocumentproperties/
---
## IDocumentProperties อินเทอร์เฟซ

แสดงคุณสมบัติของงานพรีเซนเทชัน.

```csharp
public interface IDocumentProperties
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | คืนค่า หรือ ตั้งค่าเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | คืนค่า หรือ ตั้งค่าผู้เขียนของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | คืนค่า หรือ ตั้งค่าประเภทของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | คืนค่า หรือ ตั้งค่าคอมเมนต์ของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติบริษัท. อ่าน/เขียน String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | คืนค่า หรือ ตั้งค่าสถานะเนื้อหาของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | คืนค่า หรือ ตั้งค่าประเภทเนื้อหาของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | คืนค่าจำนวนคุณสมบัติที่กำหนดเองที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | คืนค่าวันที่ที่งานพรีเซนเทชันถูกสร้าง. ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[] |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารพรีเซนเทชัน. อ่านอย่างเดียว Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติ HyperlinkBase ของเอกสาร. อ่าน/เขียน String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ถูกอัปเดตโดยผู้ผลิตเฉพาะส่วนนี้. ผู้ผลิตคนถัดไปที่เปิดเอกสารนี้จะอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติที่กำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | คืนค่า หรือ ตั้งค่าคำสำคัญของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | คืนค่าวันที่ที่งานพรีเซนเทชันถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อของผู้ที่แก้ไขงานพรีเซนเทชันเป็นครั้งสุดท้าย. อ่าน/เขียน String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | คืนค่าวันที่ที่งานพรีเซนเทชันถูกแก้ไขล่าสุด. ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกอ็อบเจกต์ IPresentation). สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนค่าจากเมธอด [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) โปรดดูตัวอย่างในสรุปเมธอด [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | ระบุว่าลิงก์ในเอกสารถูกปรับปรุงอยู่หรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์ได้รับการอัปเดต. ตั้งค่าส่วนนี้เป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติผู้จัดการ. อ่าน/เขียน String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | ระบุจำนวนรวมของคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อของแอปพลิเคชัน. อ่าน/เขียน String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | ระบุจำนวนสไลด์ในงานพรีเซนเทชันที่มีโน้ต. อ่านอย่างเดียว Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | ระบุจำนวนทั้งหมดของย่อหน้าที่พบในเอกสาร หากมี. อ่านอย่างเดียว Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | คืนค่า หรือ ตั้งค่ารูปแบบที่ตั้งใจของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | คืนค่า หรือ ตั้งค่าหมายเลขรุ่นของงานพรีเซนเทชัน. อ่าน/เขียน Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | ระบุโหมดการแสดงผลของภาพตัวอย่างเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการขยายขนาดของภาพตัวอย่างให้พอดีกับหน้าจอ. ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดการตัดส่วนของภาพตัวอย่างให้แสดงเฉพาะส่วนที่พอดีกับหน้าจอ. อ่าน/เขียน Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | กำหนดว่าการนำเสนอมีการแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | ระบุจำนวนรวมของสไลด์ในเอกสารพรีเซนเทชัน. อ่านอย่างเดียว Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | คืนค่า หรือ ตั้งค่าหัวข้อของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อเรื่องของงานพรีเซนเทชัน. อ่าน/เขียน String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | ระบุชื่อของแต่ละส่วนของเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนแนวคิดของส่วนเอกสาร. อ่านอย่างเดียว string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | ระยะเวลาการแก้ไขทั้งหมดของงานพรีเซนเทชัน. อ่าน/เขียน TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | ระบุจำนวนคำทั้งหมดที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | ล้างและกำหนดค่าเริ่มต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | ลบคุณสมบัติที่กำหนดเองทั้งหมด. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | ตรวจสอบการมีอยู่ของคุณสมบัติที่กำหนดเองด้วยชื่อที่ระบุ. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | คืนชื่อคุณสมบัติที่กำหนดเองที่ตำแหน่งที่ระบุ. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | ดึงค่าประเภท DateTime ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | ดึงค่าชนิด double ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | ดึงค่าชนิด float ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | ดึงค่าชนิด integer ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | ดึงค่า string ที่มีชื่อจากคุณสมบัติที่กำหนดเอง. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | ดึงอาเรย์ของป้ายความละเอียดจากคุณสมบัติเ�เอกสารที่กำหนดเอง (Metadata ของ Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | ลบคุณสมบัติที่กำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ตั้งค่าคุณสมบัติบูลีนที่กำหนดชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ตั้งค่าคุณสมบัติ DateTime ที่กำหนดชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ตั้งค่าคุณสมบัติ double ที่กำหนดชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ตั้งค่าคุณสมบัติ float ที่กำหนดชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ตั้งค่าคุณสมบัติ integer ที่กำหนดชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ตั้งค่าคุณสมบัติ string ที่กำหนดชื่อ. |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->