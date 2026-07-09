---
title: ISlideCollection
second_title: Aspose.Sildes สำหรับอ้างอิง API ของ .NET
description: เป็นคอลเลกชันของสไลด์
type: docs
weight: 7050
url: /th/aspose.slides/islidecollection/
---
## ISlideCollection ส่วนต่อประสาน

เป็นคอลเลกชันของสไลด์

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`ISlide`](../islide). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของส่วนที่ระบุ. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังส่วนท้ายของคอลเลกชัน. เค้าโครงที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (เค้าโครงที่เหมาะสมคือเค้าโครงที่มี Type หรือ Name เหมือนกับเค้าโครงของสไลด์ต้นฉบับ). หากไม่มีเค้าโครงที่เหมาะสม เค้าโครงของสไลด์ต้นฉบับจะถูกทำสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout เป็น false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | เพิ่มสไลด์เปล่าใหม่ไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปยังส่วนท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | คืนดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. เค้าโครงที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (เค้าโครงที่เหมาะสมคือเค้าโครงที่มี Type หรือ Name เหมือนกับเค้าโครงของสไลด์ต้นฉบับ). หากไม่มีเค้าโครงที่เหมาะสม เค้าโครงของสไลด์ต้นฉบับจะถูกทำสำเนา (หาก allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout เป็น false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกเข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | ลบการปรากฏครั้งแรกของวัตถุที่ระบุจากคอลเลกชัน. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. สไลด์จะถูกวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | สร้างและคืนอาเรย์ที่มีสไลด์ทั้งหมด. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | สร้างและคืนอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ. |

### ดูเพิ่มเติม

* ส่วนต่อประสาน [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* ส่วนต่อประสาน [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->