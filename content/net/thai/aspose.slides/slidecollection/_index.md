---
title: SlideCollection
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของคอลเลกชันของสไลด์.
type: docs
weight: 9970
url: /th/aspose.slides/slidecollection/
---
## SlideCollection คลาส

เป็นตัวแทนของคอลเลกชันของสไลด์

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | คืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. Layout ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (layout ที่เหมาะสมคือ layout ที่มี Type หรือ Name เหมือนกับ layout ของสไลด์ต้นฉบับ). หากไม่มี layout ที่เหมาะสม Layout ของสไลด์ต้นฉบับจะถูกคัดลอก (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันโดยคำนึงถึงตัวเลือกการนำเข้า pdf. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | คืนดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. Layout ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ (layout ที่เหมาะสมคือ layout ที่มี Type หรือ Name เหมือนกับ layout ของสไลด์ต้นฉบับ). หากไม่มี layout ที่เหมาะสม Layout ของสไลด์ต้นฉบับจะถูกคัดลอก (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. สไลด์จะถูกวางตั้งแต่ตำแหน่งเริ่มต้นตามลำดับที่ปรากฏในรายการ. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | สร้างและคืนอาเรย์ที่มีสไลด์ทั้งหมด. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | สร้างและคืนอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ. ดัชนีของสไลด์แรกที่ต้องเพิ่ม จำนวนของสไลด์ที่ต้องเพิ่ม. |

### ดูเพิ่มเติม

* คลาส [DomObject&lt;TParent&gt;](../domobject-1)
* คลาส [Presentation](../presentation)
* อินเทอร์เฟซ [ISlideCollection](../islidecollection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->