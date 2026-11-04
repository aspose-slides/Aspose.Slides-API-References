---
title: IShapeCollection
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงคอลเลกชันของรูปร่าง.
type: docs
weight: 7000
url: /th/aspose.slides/ishapecollection/
---
## IShapeCollection อินเทอร์เฟซ

เป็นคอลเลกชันของรูปร่าง

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | รับเอาอีลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | รับอ็อบเจกต์กลุ่มรูปพาเรนท์สำหรับคอลเลกชันของรูปร่าง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |

## เมธอด

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างกรอบเสียงใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างกรอบเสียงใหม่ที่มีไฟล์ WAV ฝังอยู่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างออโต้เชปใหม่ด้วยการจัดรูปแบบเริ่มต้นและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างออโต้เชปใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตเริ่มต้น. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างรูปเชื่อมต่อใหม่ด้วยการจัดรูปแบบเทมเพลตเริ่มต้นและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างรูปเชื่อมต่อใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้การจัดรูปแบบเทมเพลตเริ่มต้น. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างที่เพิ่มเข้าไป. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างแต่ละส่วน, และเพิ่มกลุ่มที่ได้ไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | สร้างออโต้เชปสี่เหลี่ยมใหม่เพื่อเป็นโฮสต์เนื้อหาคณิตศาสตร์และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างเฟรมวัตถุ OLE ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างไดอะแกรม SmartArt และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่าง. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | ลบรูปร่างทั้งหมดออกจากคอลเลกชันรูปร่าง. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | คืนค่าดัชนีฐานศูนย์ของการปรากฏครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างกรอบเสียงใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างกรอบเสียงใหม่ที่มีไฟล์ WAV ฝังอยู่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างออโต้เชปใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, ด้วยการจัดรูปแบบเทมเพลตเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างออโต้เชปใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตเริ่มต้น. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของซีรีส์, และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, ด้วยการจัดรูปแบบเทมเพลตเริ่มต้น. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างรูปเชื่อมต่อใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจใช้การจัดรูปแบบเทมเพลตเริ่มต้น. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างที่เพิ่มเข้าไป. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างเฟรมวัตถุ OLE ใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกเข้าในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | เอาการปรากฏครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันรูปร่าง, เริ่มวางตั้งแต่ตำแหน่งที่กำหนด. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | สร้างและคืนค่าอาเรย์ที่มีรูปร่างทั้งหมด. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | สร้างและคืนค่าอาเรย์ที่มีรูปร่างทั้งหมดในช่วงที่ระบุ. |

### ดูเพิ่มเติม

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->