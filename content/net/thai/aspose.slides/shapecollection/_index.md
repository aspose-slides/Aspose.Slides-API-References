---
title: ShapeCollection
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงคอลเลกชันของรูปร่าง.
type: docs
weight: 9860
url: /th/aspose.slides/shapecollection/
---
## ShapeCollection คลาส

แสดงชุดของรูปร่าง.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | คืนค่าแสดงว่าการเข้าถึงคอลเลกชันมีการทำให้เป็นแบบประสาน (ปลอดภัยต่อเธรด). อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | รับอ็อบเจ็กต์กลุ่มรูปพ่อแม่สำหรับคอลเลกชันของรูปร่าง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | คืนค่ารากของการประสาน. อ่านอย่างเดียว Object. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างเฟรมออดิโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรงโดยใช้วัตถุออดิโอที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างเฟรมออดิโอใหม่พร้อมไฟล์ WAV ฝังในตัวและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. ออดิโอที่ฝังจะถูกเพิ่มในคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับไฟล์ออดิโอภายนอกและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างออโต้เชปใหม่ด้วยการจัดรูปแบบค่าเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างออโต้เชปใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง, โดยอาจเริ่มต้นด้วยการจัดรูปแบบเทมเพลตค่าเริ่มต้น. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของชุดข้อมูล, และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของชุดข้อมูล, และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง, โดยอาจใช้การจัดรูปแบบเทมเพลตค่าเริ่มต้น. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. รูปร่างที่คัดลอกจะรักษาตำแหน่งและขนาดเดิม. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. รูปร่างใหม่จะรักษาความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างเชื่อมต่อเชปใหม่ด้วยสไตล์เทมเพลตค่าเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างเชื่อมต่อเชปใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง, โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปทรงเปล่าใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปทรงใด ๆ ที่เพิ่มเข้าไป. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปทรงใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปทรงแยกส่วน, และเพิ่มกลุ่มที่ได้ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | สร้างสี่เหลี่ยมออโต้เชปใหม่เพื่อเก็บเนื้อหาทางคณิตศาสตร์และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมภาพใหม่ที่บรรจุภาพที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างแผนผัง SmartArt และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปทรง. |
| [Clear](../../aspose.slides/shapecollection/clear)() | ลบรูปทรงทั้งหมดจากคอลเลกชันรูปทรง. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | คัดลอกทั้งหมดขององค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | คืนดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างเฟรมออดิโอใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุโดยใช้วัตถุออดิโอที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างเฟรมออดิโอใหม่พร้อมไฟล์ WAV ฝังในตัวและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. ออดิโอที่ฝังจะถูกเพิ่มในคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างเฟรมออดิโอใหม่ที่เชื่อมโยงกับไฟล์ออดิโอภายนอกและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างออโต้เชปใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุโดยใช้การจัดรูปแบบเทมเพลตค่าเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างออโต้เชปใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, โดยอาจเริ่มต้นด้วยสไตล์เทมเพลตค่าเริ่มต้น. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของชุดข้อมูล, และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่างของชุดข้อมูล, และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. รูปร่างที่คัดลอกจะรักษาตำแหน่งและขนาดเดิม. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะรักษาความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างเชื่อมต่อเชปใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุโดยใช้สไตล์เทมเพลตค่าเริ่มต้น. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างเชื่อมต่อเชปใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์เทมเพลตค่าเริ่มต้น. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปทรงเปล่าใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปทรงใด ๆ ที่เพิ่มเข้าไป. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปทรง. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปทรง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปทรง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันรูปทรง, โดยเริ่มวางที่ดัชนีที่กำหนด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | สร้างและคืนค่าอาเรย์ที่บรรจุรูปทรงทั้งหมด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | สร้างและคืนค่าอาเรย์ที่บรรจุรูปทรงทั้งหมดในช่วงที่ระบุ. |

### ดูเพิ่ม

* คลาส [DomObject&lt;TParent&gt;](../domobject-1)
* คลาส [GroupShape](../groupshape)
* อินเทอร์เฟซ [IShapeCollection](../ishapecollection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->