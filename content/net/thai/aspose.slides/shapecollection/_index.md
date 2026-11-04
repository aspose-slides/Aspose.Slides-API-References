---
title: ShapeCollection
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวแทนของคอลเลกชันของรูปร่าง.
type: docs
weight: 9880
url: /th/aspose.slides/shapecollection/
---
## ShapeCollection คลาส

เป็นตัวแทนของคอลเลกชันของรูปร่าง

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริง. อ่านอย่างเดียว Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันมีการประสาน (ปลอดภัยต่อเธรด). อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | รับวัตถุรูปแบบกลุ่มแม่สำหรับคอลเลกชันของรูปร่าง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | คืนค่ารากของการประสาน. อ่านอย่างเดียว Object. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับแทร็กซีดีและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับไฟล์เสียงภายนอกและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างออโตช่วรูปใหม่ด้วยการจัดรูปแบบเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างออโตช่วรูปใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจกำหนดค่าเริ่มต้นด้วยรูปแบบเทมเพลตเริ่มต้นได้. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างรูปเชื่อมต่อใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง, โดยอาจใช้สไตล์เทมเพลตเริ่มต้นได้. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างแยกส่วน, และเพิ่มกลุ่มที่ได้ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | สร้างออโตช่วนสี่เหลี่ยมใหม่เพื่อเป็นโฮสต์เนื้อหาคณิตศาสตร์และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่ประกอบด้วยภาพที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างแผนผัง SmartArt และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง. |
| [Clear](../../aspose.slides/shapecollection/clear)() | ลบรูปร่างทั้งหมดจากคอลเลกชันรูปร่าง. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | คืนค่าดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับแทร็กซีดีและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างเฟรมเสียงใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างเฟรมเสียงใหม่พร้อมไฟล์ WAV ฝังและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. เสียงที่ฝังอยู่จะถูกเพิ่มไปยังคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างเฟรมเสียงใหม่ที่เชื่อมต่อกับไฟล์เสียงภายนอกและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างออโตช่วรูปใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยใช้การจัดรูปแบบเทมเพลตเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างออโตช่วรูปใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจกำหนดค่าเริ่มต้นด้วยสไตล์เทมเพลตเริ่มต้นได้. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของต้นฉบับ. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างรูปเชื่อมต่อใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างรูปเชื่อมต่อใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ, โดยอาจใช้สไตล์เทมเพลตเริ่มต้นได้. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างเฟรมอ็อบเจกต์ OLE ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างเฟรมรูปภาพใหม่ที่ประกอบด้วยภาพที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างเฟรม Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างเฟรม Summary Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างเฟรมวิดีโอใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างเฟรม Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างเฟรม Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันรูปร่าง. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุจากคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันรูปร่าง. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันรูปร่าง, เริ่มวางที่ดัชนีที่กำหนด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | สร้างและคืนค่าอาร์เรย์ที่บรรจุรูปร่างทั้งหมด. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | สร้างและคืนค่าอาร์เรย์ที่บรรจุรูปร่างทั้งหมดในช่วงที่ระบุ. |

### ดูเพิ่มเติม

* คลาส [DomObject&lt;TParent&gt;](../domobject-1)
* คลาส [GroupShape](../groupshape)
* อินเทอร์เฟซ [IShapeCollection](../ishapecollection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->