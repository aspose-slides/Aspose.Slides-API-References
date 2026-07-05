---
title: DocumentProperties
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคุณสมบัติของการนำเสนอ.
type: docs
weight: 2790
url: /th/aspose.slides/documentproperties/
---
## DocumentProperties คลาส

แสดงคุณสมบัติของการนำเสนอ

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [DocumentProperties](documentproperties)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [`DocumentProperties`](../documentproperties). |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | คืนค่า或กำหนดเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | คืนค่า或กำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | คืนค่าหรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | คืนค่า或กำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | คืนค่า或กำหนดคุณสมบัติบริษัท. อ่าน/เขียน String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | คืนค่า或กำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | คืนค่า或กำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | คืนค่าจำนวนคุณสมบัติกำหนดเองที่มีอยู่ในคอลเลกชันจริง. อ่านอย่างเดียว Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | คืนค่าหรือกำหนดวันที่สร้างการนำเสนอ. ค่ามีหน่วยเป็น UTC. อ่าน/เขียน DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | บ่งบอกการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | คืนค่าจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | คืนค่า或กำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. อ่าน/เขียน String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | กำหนดให้ลิงก์หนึ่งหรือมากกว่าถูกอัปเดตเฉพาะในส่วนนี้โดยผู้สร้าง. ผู้สร้างคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | คืนค่า或กำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | คืนค่า或กำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งล่าสุด. อ่าน/เขียน DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | คืนค่าชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. อ่าน/เขียน String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. ค่ามีหน่วยเป็น UTC. อ่านอย่างเดียวในกรณี Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในระหว่างกระบวนการบันทึกวัตถุ IPresentation). สามารถเปลี่ยนได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนค่าจากเมธอด [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) กรุณาดูตัวอย่างในสรุปเมธอด [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | บ่งบอกว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. ตั้งค่าเป็น **true** เพื่อระบุว่าลิงก์อัปเดตแล้ว. ตั้งค่าเป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | คืนค่า或กำหนดคุณสมบัติผู้จัดการ. อ่าน/เขียน String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | คืนค่าจำนวนรวมของคลิปเสียงหรือวิดีโอที่มีอยู่ในเอกสาร. อ่านอย่างเดียว Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | คืนค่า或กำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | คืนค่าจำนวนสไลด์ในการนำเสนอที่มีบันทึกย่อ. อ่านอย่างเดียว Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | คืนค่าจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี). อ่านอย่างเดียว Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | คืนค่า或กำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | คืนค่าหรือกำหนดหมายเลขการแก้ไขของการนำเสนอ. อ่าน/เขียน Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | บ่งบอกโหมดการแสดงผลของรูปย่อเอกสาร. ตั้งค่าเป็น **true** เพื่อเปิดการปรับขนาดรูปย่อให้พอดีจอแสดงผล. ตั้งค่าเป็น **false** เพื่อเปิดการตัดรูปย่อให้แสดงเฉพาะส่วนที่พอดีจอ. อ่าน/เขียน Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | กำหนดว่าการนำเสนอนี้ถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | คืนค่าจำนวนสไลด์ทั้งหมดในเอกสารการนำเสนอ. อ่านอย่างเดียว Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | คืนค่า或กำหนดหัวข้อของการนำเสนอ. อ่าน/เขียน String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | คืนค่า或กำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | ระบุชื่อส่วนของแต่ละส่วนเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนเอกสารจริงแต่เป็นการแสดงตัวแทนเชิงแนวคิดของส่วนเอกสาร. อ่านอย่างเดียว string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | ล้างและตั้งค่าพื้นฐานสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | ลบคุณสมบัติกำหนดเองทั้งหมด. |
| [Clone](../../aspose.slides/documentproperties/clone)() | คัดลอกอ็อบเจ็กต์ปัจจุบัน |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | คัดลอกอ็อบเจ็กต์ปัจจุบัน |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองด้วยชื่อที่ระบุ. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | คืนชื่อคุณสมบัติกำหนดเองตามดัชนีที่ระบุ. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | ดึงค่า DateTime ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | ดึงค่า double ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | ดึงค่า float ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | ดึงค่า integer ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | ดึงค่า string ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | ดึงอาร์เรย์ของป้ายกำกับความละเอียดจากคุณสมบัติเข้ากเอกสาร (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | ลบคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | ตั้งค่าคุณสมบัติบูลีนที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | ตั้งค่าคุณสมบัติ DateTime ที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | ตั้งค่าคุณสมบัติ double ที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | ตั้งค่าคุณสมบัติ float ที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | ตั้งค่าคุณสมบัติ integer ที่มีชื่อ. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | ตั้งค่าคุณสมบัติ string ที่มีชื่อ. |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีเข้าถึงคุณสมบัติ built-in ของ PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนการนำเสนอ
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// สร้างการอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// แสดงคุณสมบัติ builtin
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแก้ไขคุณสมบัติ built-in ของ PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทน Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// สร้างการอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// ตั้งค่าคุณสมบัติ builtin
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// บันทึกการนำเสนอของคุณไปยังไฟล์
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IDocumentProperties](../idocumentproperties)
* อินเทอร์เฟซ [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->