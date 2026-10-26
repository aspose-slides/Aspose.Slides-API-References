---
title: IShapeCollection
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงคอลเลกชันของรูปร่าง.
type: docs
weight: 6980
url: /th/aspose.slides/ishapecollection/
---
## IShapeCollection ส่วนต่อประสาน

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | รับอ็อบเจ็กต์กลุ่มรูปร่างแม่สำหรับคอลเลกชันรูปร่าง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่ด้วยไฟล์ WAV ฝังและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. เสียงที่ฝังจะถูกเพิ่มลงในคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างอัตโนมัติรูปร่างใหม่ด้วยการฟอร์แมตเริ่มต้นและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างอัตโนมัติรูปร่างใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง โดยอาจกำหนดฟอร์แมตเทมเพลตเริ่มต้น. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, ตั้งค่าข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, ตั้งค่าข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. รูปร่างที่คล.clone จะคงตำแหน่งและขนาดเดิม. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างเชื่อมต่อรูปร่างใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างเชื่อมต่อรูปร่างใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอใส่รูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปร่างใหม่, แปลงรูปภาพ SVG ที่ระบุเป็นรูปร่างแยกส่วน, แล้วเพิ่มกลุ่มที่ได้ไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | สร้างอัตโนมัติรูปร่างสี่เหลี่ยมใหม่เพื่อเป็นโฮสต์เนื้อหาคณิตศาสตร์และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมภาพใหม่ที่มีภาพที่ระบุและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างไดอะแกรม SmartArt ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างเฟรมวีดีโอใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างเฟรมวีดีโอใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังท้ายของคอลเลกชันรูปร่าง. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | ลบรูปร่างทั้งหมดออกจากคอลเลกชันรูปร่าง. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | ส่งคืนดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่ด้วยไฟล์ WAV ฝังและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. เสียงที่ฝังจะถูกเพิ่มลงในคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างอัตโนมัติรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้ฟอร์แมตเทมเพลตเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างอัตโนมัติรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยอาจกำหนดฟอร์แมตเทมเพลตเริ่มต้น. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, ตั้งค่าข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, ตั้งค่าข้อมูลชุดตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างที่คล.clone จะคงตำแหน่งและขนาดเดิม. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างเชื่อมต่อรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้ฟอร์แมตเทมเพลตเริ่มต้น. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างเชื่อมต่อรูปร่างใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยอาจใช้สไตล์เทมเพลตเริ่มต้น. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอใส่รูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมภาพใหม่ที่มีภาพที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างเฟรมวีดีโอใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | ลบการปรากฏครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุหลายรูปร่างภายในคอลเลกชันรูปร่างโดยจัดวางเริ่มจากตำแหน่งที่กำหนด. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | สร้างและส่งกลับอาเรย์ที่ประกอบด้วยรูปร่างทั้งหมด. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | สร้างและส่งกลับอาเรย์ที่ประกอบด้วยรูปร่างทั้งหมดในช่วงที่ระบุ. |

### ดูเพิ่มเติม

* ส่วนต่อประสาน [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* ส่วนต่อประสาน [IShape](../ishape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->