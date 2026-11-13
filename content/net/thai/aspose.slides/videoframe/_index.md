---
title: VideoFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงคลิปวิดีโอบนสไลด์หนึ่ง.
type: docs
weight: 11740
url: /th/aspose.slides/videoframe/
---
## VideoFrame คลาส

Represents a video clip on a slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวเรื่องของข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่า shape จะเรนเดอร์ในโหมดแสดงผลขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | ดึงคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ video frame. คุณสมบัตินี้เป็นอ่านอย่างเดียวและส่งคืน [`ICaptionsCollection`](../icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนตำแหน่งเชื่อมต่อบน shape. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของ shape. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจกต์ EffectFormat ที่ประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | ส่งคืนหรือกำหนดออบเจกต์วิดีโอที่ฝังไว้. อ่าน/เขียน [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจกต์ FillFormat ที่ประกอบด้วยคุณสมบัติการเติมสำหรับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของเฟรม shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ดึงหรือกำหนดความสูงของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่า shape จะซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | กำหนดว่า VideoFrame จะซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดลิงก์ที่กำหนดสำหรับคลิกเม้าส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดลิงก์ที่กำหนดสำหรับเม้าส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่า PictureFrame เป็นออบเจกต์ Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ดึงหรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจกต์ LineFormat ที่ประกอบด้วยคุณสมบัติการวาดเส้นของ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติการวาดเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของ shape. ต้องไม่เป็น null. ใช้ค่า string ว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนรหัสประจำตัวที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape จากที่ใดในเอกสารได้อย่างเชื่อถือได้. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจกต์ GroupShape พาเรนท์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นส่งคืน null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนอ็อบเจกต์ PictureFillFormat สำหรับ picture frame. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืนล็อกของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของ shape. ส่งคืน null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | กำหนดว่าวิดีโอวนซ้ำหรือไม่. อ่าน/เขียน Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนการนำเสนอพาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติแบบดิบของเฟรม shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ส่งคืนหรือกำหนดสเกลความสูง (สัมพันธ์กับขนาดรูปต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ส่งคืนหรือกำหนดสเกลความกว้าง (สัมพันธ์กับขนาดรูปต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | กำหนดว่าวิดีโอจะรีวายด์อัตโนมัติไปยังจุดเริ่มต้นทันทีเมื่อวิดีโอเล่นจบหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฏิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืนล็อกของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนอ็อบเจกต์สไตล์ของ shape. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดของชุด [`ShapeType`](../shapetype) ยกเว้นเส้นทุกรูปแบบ: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนท์ของ shape. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติของ shape. หมายเหตุ: สามารถส่งคืน null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | ตัดส่วนท้าย [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | ตัดส่วนเริ่มต้น [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนรหัสภายในระดับการนำเสนอที่ออกแบบให้ใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์แบบถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | ส่งคืนหรือกำหนดระดับเสียง. อ่าน/เขียน [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | ส่งคืนหรือกำหนดระดับเสียงวิดีโอตามเปอร์เซ็นต์. ค่าถูกแสดงเป็นเปอร์เซ็นต์จาก 0 ถึง 100. ใช้คุณสมบัตินี้เพื่ออ่านหรือกำหนดค่าระดับเสียงที่แม่นยำกว่าระดับที่กำหนดไว้ล่วงหน้าผ่านคุณสมบัติ [`Volume`](./volume). อ่าน/เขียน Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | ดึงหรือกำหนดความกว้างของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | ดึงหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | ดึงหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของ shape ใน z-order. Shapes[0] ส่งคืน shape ที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่อยู่ด้านหน้าของ z-order. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้กับที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาร์เรย์ของสมาชิกของ shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน shape placeholder พื้นฐาน (shape จากเลเอาต์และ/หรือมาสเตอร์สไลด์ที่ shape ปัจจุบันสืบทอดมาจาก). ส่งคืน null หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของ path ของ shape เรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนรูปภาพย่อของ shape. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนรูปภาพย่อของ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | ดึงขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของ shape จากอ็อบเจกต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของ shape จากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe)
* อินเทอร์เฟซ [IVideoFrame](../ivideoframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->