---
title: DocumentProperties
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคุณสมบัติของการนำเสนอ.
type: docs
weight: 2810
url: /th/aspose.slides/documentproperties/
---
## DocumentProperties คลาส

แสดงคุณสมบัติของการนำเสนอ.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [DocumentProperties](documentproperties)() | สร้างอินสแตนซ์ใหม่ของคลาส [`DocumentProperties`](../documentproperties). |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | คืนค่า หรือกำหนดหมวดหมู่ของการนำเสนอ. อ่าน/เขียน String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | คืนค่าจำนวนคุณสมบัติกำหนดเองที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | คืนค่าวันที่ที่การนำเสนอถูกสร้าง. ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | คืนค่าจำนวนสไลด์ที่ซ่อนไว้ในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. อ่าน/เขียน String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ถูกอัปเดตโดยผู้ผลิตโดยเฉพาะในส่วนนี้. ผู้ผลิตต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | คืนค่า หรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | คืนค่าวันที่ที่การนำเสนอถูกพิมพ์ครั้งล่าสุด. อ่าน/เขียน DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. อ่าน/เขียน String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | คืนค่าวันที่ที่การนำเสนอถูกแก้ไขล่าสุด. ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในระหว่างกระบวนการบันทึกออบเจกต์ IPresentation). สามารถเปลี่ยนได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนค่าจากเมธอด [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) โปรดดูตัวอย่างในสรุปเมธอด [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | ระบุว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์ถูกอัปเดต. ตั้งค่าส่วนนี้เป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติ manager. อ่าน/เขียน String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | คืนค่าจำนวนทั้งหมดของคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | คืนค่าจำนวนสไลด์ในการนำเสนอที่มีโน้ต. อ่านอย่างเดียว Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | คืนค่าจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี). อ่านอย่างเดียว Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | คืนค่า หรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | คืนค่า หรือกำหนดหมายเลขการแก้ไขของการนำเสนอ. อ่าน/เขียน Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | ระบุโหมดการแสดงผลของภาพย่อเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดใช้การปรับสเกลของภาพย่อเอกสารให้ตรงกับหน้าจอ. ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดใช้การตัดแบบครอบภาพย่อเพื่อแสดงเฉพาะส่วนที่พอดีกับหน้าจอ. อ่าน/เขียน Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | คืนค่าจำนวนทั้งหมดของสไลด์ในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. อ่าน/เขียน String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | ระบุชื่อของแต่ละส่วนเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนส่วนของเอกสารเชิงแนวคิด. อ่านอย่างเดียว string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | ล้างและตั้งค่าดีฟอลต์ให้กับคุณสมบัติในตัวทั้งหมด. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | ลบคุณสมบัติกำหนดเองทั้งหมด. |
| [Clone](../../aspose.slides/documentproperties/clone)() | ทำสำเนาออบเจกต์ปัจจุบัน |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | ทำสำเนาออบเจกต์ปัจจุบัน |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองที่มีชื่อระบุ. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | คืนค่าชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่ระบุ. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | รับค่าบูลีนที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | รับค่า DateTime ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | รับค่าดับเบิลที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | รับค่าแฟลตที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | รับค่าจำนวนเต็มที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | รับค่าสตริงที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | รับอาเรย์ของป้ายกำกับความอ่อนไหวจากคุณสมบัติเบื้องต้นของเอกสาร (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | ลบคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ตั้งค่าคุณสมบัติกำหนดเองแบบบูลีนที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ตั้งค่าคุณสมบัติกำหนดเองแบบ DateTime ที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ตั้งค่าคุณสมบัติกำหนดเองแบบดับเบิลที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ตั้งค่าคุณสมบัติกำหนดเองแบบแฟลตที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ตั้งค่าคุณสมบัติกำหนดเองแบบจำนวนเต็มที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ตั้งค่าคุณสมบัติกำหนดเองแบบสตริงที่มีชื่อ. |

### ตัวอย่าง

ตัวอย่างต่อไนี้แสดงวิธีเข้าถึงคุณสมบัติในตัวของการนำเสนอ PowerPoint.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงการนำเสนอ
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// สร้างการอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// แสดงคุณสมบัติในตัว
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

ตัวอย่างต่อไนี้แสดงวิธีแก้ไขคุณสมบัติในตัวของการนำเสนอ PowerPoint.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของ Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// สร้างการอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// ตั้งค่าคุณสมบัติในตัว
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// บันทึกการนำเสนอของคุณเป็นไฟล์
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IDocumentProperties](../idocumentproperties)
* อินเทอร์เฟซ [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->