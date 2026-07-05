---
title: ShapeCollection
second_title: Aspose.Sildes สำหรับ .NET API อ้างอิง
description: แสดงถึงคอลเลกชันของรูปทรง.
type: docs
weight: 9860
url: /th/aspose.slides/shapecollection/
---
## ShapeCollection คลาส

แสดงถึงคอลเลกชันของรูปร่าง.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | ส่งคืนค่าแสดงว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบประสาน (ปลอดภัยต่อเธรด). อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | รับอ็อบเจ็กต์รูปกลุ่มพาเรนท์สำหรับคอลเลกชันของรูปทรง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | ส่งคืนรากของการประสาน. อ่านอย่างเดียว Object. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรงโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. ไฟล์เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างรูปร่างอัตโนมัติใหม่ด้วยรูปแบบค่าเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างรูปร่างอัตโนมัติใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง, โดยอาจเริ่มต้นด้วยรูปแบบเท็มเพลตค่าเริ่มต้น. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างรูปทรงเชื่อมต่อใหม่ด้วยสไตล์เท็มเพลตค่าเริ่มต้นและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างรูปทรงเชื่อมต่อใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง, โดยอาจใช้สไตล์เท็มเพลตค่าเริ่มต้น. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปทรงว่างใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างที่เพิ่มเข้ามา. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปทรงใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างแยกต่างหาก, แล้วเพิ่มกลุ่มที่ได้ลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | สร้างสี่เหลี่ยมอัตโนมัติใหม่เพื่อเก็บเนื้อหาทางคณิตศาสตร์และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างแผนผัง SmartArt และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างเฟรมวีดีโอใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างเฟรมวีดีโอใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง. |
| [Clear](../../aspose.slides/shapecollection/clear)() | ลบรูปร่างทั้งหมดออกจากคอลเลกชันรูปทรง. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | ส่งคืน enumerator ที่วนผ่านคอลเลกชัน. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | ส่งคืนดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ที่ฝังอยู่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. ไฟล์เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, ใช้รูปแบบเท็มเพลตค่าเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างรูปร่างอัตโนมัติใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, โดยอาจเริ่มต้นด้วยสไตล์เท็มเพลตค่าเริ่มต้น. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างรูปทรงเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, ใช้สไตล์เท็มเพลตค่าเริ่มต้น. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างรูปทรงเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์เท็มเพลตค่าเริ่มต้น. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปทรงว่างใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างที่เพิ่มเข้ามา. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างเฟรมอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างเฟรมวีดีโอใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปทรง. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันรูปทรง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปทรง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุหลายรูปภายในคอลเลกชันรูปทรง, เริ่มวางจากตำแหน่งที่กำหนด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | สร้างและส่งคืนอาเรย์ที่บรรจุรูปร่างทั้งหมด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | สร้างและส่งคืนอาเรย์ที่บรรจุรูปร่างทั้งหมดในช่วงที่ระบุ. |

### ดูเพิ่มเติม

* คลาส [DomObject&lt;TParent&gt;](../domobject-1)
* คลาส [GroupShape](../groupshape)
* อินเทอร์เฟซ [IShapeCollection](../ishapecollection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->