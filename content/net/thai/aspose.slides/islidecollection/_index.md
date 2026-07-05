---
title: ISlideCollection
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงคอลเลกชันของสไลด์
type: docs
weight: 7050
url: /th/aspose.slides/islidecollection/
---
## ISlideCollection อินเทอร์เฟซ

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Gets the element at the specified index. Read-only [`ISlide`](../islide). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งท้ายของคอลเลกชัน |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งท้ายของคอลเลกชัน |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งท้ายของส่วนที่ระบุ |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งท้ายของคอลเลกชัน เลย์เอาต์ที่เหมาะสมจะถูกเลือกอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เดียวกับเลย์เอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลย์เอาต์ที่เหมาะสมแล้วเลย์เอาต์ของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะทำให้เกิด PptxEditException (ถ้า allowCloneMissingLayout เป็น false) |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งท้ายของคอลเลกชัน |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้าย |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้ายโดยพิจารณาตัวเลือก PdfImportOptions |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มเข้าคอลเลกชันที่ตำแหน่งท้ายโดยพิจารณาตัวเลือก PdfImportOptions |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน เลย์เอาต์ที่เหมาะสมจะถูกเลือกอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เดียวกับเลย์เอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลย์เอาต์ที่เหมาะสมแล้วเลย์เอาต์ของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะทำให้เกิด PptxEditException (ถ้า allowCloneMissingLayout เป็น false) |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่กำหนด |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุจากคอลเลกชัน |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ สไลด์จะถูกวางตั้งแต่ดัชนีตามลำดับที่ปรากฏในรายการ |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมด |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* อินเทอร์เฟซ [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->