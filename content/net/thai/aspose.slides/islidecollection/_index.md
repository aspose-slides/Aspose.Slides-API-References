---
title: ISlideCollection
second_title: Aspose.Sildes สำหรับ .NET - เอกสารอ้างอิง API
description: แทนคอลเลกชันของสไลด์
type: docs
weight: 7070
url: /th/aspose.slides/islidecollection/
---
## อินเทอร์เฟซ ISlideCollection

แทนคอลเลกชันของสไลด์

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ. อ่านอย่างเดียว [`ISlide`](../islide). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปที่ท้ายคอลเลกชัน. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปที่ท้ายคอลเลกชัน. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | เพิ่มสำเนาของสไลด์ที่ระบุไปที่ท้ายของส่วนที่ระบุ. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปที่ท้ายของคอลเลกชัน การจัดรูปแบบที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (การจัดรูปแบบที่เหมาะสมคือการจัดรูปแบบที่มี Type หรือ Name เหมือนกับการจัดรูปแบบของสไลด์ต้นฉบับ) หากไม่มีการจัดรูปแบบที่เหมาะสม การจัดรูปแบบของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | เพิ่มสไลด์เปล่าใหม่ไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปที่ท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มไปที่ท้ายของคอลเลกชันโดยพิจารณาตัวเลือกการนำเข้า pdf. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | คืนดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | แทรกสำเนของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | แทรกสำเนของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน การจัดรูปแบบที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (การจัดรูปแบบที่เหมาะสมคือการจัดรูปแบบที่มี Type หรือ Name เหมือนกับการจัดรูปแบบของสไลด์ต้นฉบับ) หากไม่มีการจัดรูปแบบที่เหมาะสม การจัดรูปแบบของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
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
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | ลบการพบครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุของคอลเลกชัน. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางตั้งแต่ดัชนีที่ระบุตามลำดับที่ปรากฏในรายการ. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | สร้างและคืนอาร์เรย์ที่มีสไลด์ทั้งหมด. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | สร้างและคืนอาร์เรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* อินเทอร์เฟซ [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->