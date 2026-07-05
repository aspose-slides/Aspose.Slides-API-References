---
title: IShapeCollection
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของคอลเลกชันของรูปร่าง.
type: docs
weight: 6980
url: /th/aspose.slides/ishapecollection/
---
## IShapeCollection อินเทอร์เฟซ

เป็นตัวแทนของคอลเลกชันของรูปร่าง

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | ดึงเอาอีลีเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | ดึงอ็อบเจ็กต์รูปร่างกลุ่มแม่สำหรับคอลเลกชันของรูปร่าง. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |

## เมธอด

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | สร้างกรอบเสียงใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่างโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | สร้างกรอบเสียงใหม่ด้วยไฟล์ WAV ฝังตัวและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. เสียงที่ฝังจะถูกเพิ่มในคอลเลกชัน Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | สร้างออโต้ชาพใหม่ด้วยการฟอร์แมตเริ่มต้นและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | สร้างออโต้ชาพใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง, โดยสามารถกำหนดให้ใช้ฟอร์แมตเทมเพลตเริ่มต้นได้. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดเดิม. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | สร้างคอนเนกเตอร์รูปแบบใหม่ด้วยสไตล์เทมเพลตเริ่มต้นและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | สร้างคอนเนกเตอร์รูปแบบใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง, โดยสามารถกำหนดให้ใช้สไตล์เทมเพลตเริ่มต้นได้. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | สร้างกลุ่มรูปร่างใหม่, แปลงรูปภาพ SVG ที่ระบุเป็นรูปร่างแยกแต่ละชิ้น, แล้วเพิ่มกลุ่มที่ได้ลงท้ายคอลเลกชันของรูปร่าง. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | สร้างออโต้ชาพสี่เหลี่ยมใหม่เพื่อเป็นโฮสต์เนื้อหาทางคณิตศาสตร์และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | สร้างกรอบอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | สร้างกรอบอ็อบเจ็กต์ OLE ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | สร้างกรอบรูปภาพใหม่โดยใส่รูปที่ระบุและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | สร้างกรอบ Section Zoom ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | สร้างกรอบ Section Zoom ใหม่โดยมีรูปภาพที่กำหนดไว้ล่วงหน้าและเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | สร้างไดอะแกรม SmartArt และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | สร้างกรอบ Summary Zoom ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | สร้างตารางใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | สร้างกรอบวิดีโอใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | สร้างกรอบวิดีโอใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | สร้างกรอบ Zoom ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | สร้างกรอบ Zoom ใหม่และเพิ่มลงท้ายคอลเลกชันของรูปร่าง. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | ลบรูปร่างทั้งหมดออกจากคอลเลกชันของรูปร่าง. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | คืนค่าตำแหน่งดัชนีเริ่มต้น (zero-based) ของการพบครั้งแรกของรูปร่างที่ระบุในคอลเลกชัน. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับแทร็ก CD และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | สร้างกรอบเสียงใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุโดยใช้วัตถุเสียงที่มีอยู่จากรายการ Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | สร้างกรอบเสียงใหม่ด้วยไฟล์ WAV ฝังตัวและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. เสียงที่ฝังจะถูกเพิ่มในคอลเลกชัน Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | สร้างกรอบเสียงใหม่ที่เชื่อมโยงกับไฟล์เสียงภายนอกและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | สร้างออโต้ชาพใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, ใช้ฟอร์แมตเทมเพลตเริ่มต้น. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | สร้างออโต้ชาพใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, โดยสามารถกำหนดให้ใช้สไตล์เทมเพลตเริ่มต้นได้. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลซีรีส์ตัวอย่างและการตั้งค่า, แล้วแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดเดิม. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | สร้างคอนเนกเตอร์รูปแบบใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, ใช้สไตล์เทมเพลตเริ่มต้น. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | สร้างคอนเนกเตอร์รูปแบบใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ, โดยสามารถกำหนดให้ใช้สไตล์เทมเพลตเริ่มต้นได้. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | สร้างกลุ่มรูปร่างเปล่าใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่เพิ่มเข้าไป. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | สร้างกรอบอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | สร้างกรอบอ็อบเจ็กต์ OLE ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | สร้างกรอบรูปภาพใหม่โดยใส่รูปที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | สร้างกรอบ Section Zoom ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | สร้างกรอบ Section Zoom ใหม่โดยมีรูปภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | สร้างกรอบ Summary Zoom ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | สร้างตารางใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | สร้างกรอบวิดีโอใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | สร้างกรอบ Zoom ใหม่และแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | สร้างกรอบ Zoom ใหม่โดยมีรูปภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่ระบุ. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | ลบการพบครั้งแรกของรูปร่างที่ระบุออกจากคอลเลกชันของรูปร่าง. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | ลบรูปร่างที่ตำแหน่งที่ระบุออกจากคอลเลกชันของรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันของรูปร่าง. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | ย้ายรูปร่างที่ระบุภายในคอลเลกชันของรูปร่าง, เริ่มจากตำแหน่งที่ระบุ. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | สร้างและคืนค่าอาเรย์ที่บรรจุรูปร่างทั้งหมด. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | สร้างและคืนค่าอาเรย์ที่บรรจุรูปร่างทั้งหมดในช่วงที่ระบุ. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->