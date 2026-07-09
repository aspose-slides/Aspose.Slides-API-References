---
title: VideoFrame
second_title: Aspose.Sildes สำหรับเอกสารอ้างอิง API ของ .NET
description: แสดงคลิปวิดีโอบนสไลด์.
type: docs
weight: 11720
url: /th/aspose.slides/videoframe/
---
## VideoFrame คลาส

แสดงคลิปวิดีโอบนสไลด์.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | คืนค่าคอลเลกชันของค่าการปรับของรูปทรง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่ที่เกี่ยวข้องกับรูปทรึง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดหัวข้อของข้อความแทนที่ที่เกี่ยวข้องกับรูปทรึง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติระบุว่ารูปทรึงจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | รับคอลเลกชันของคำบรรยายปิดที่เกี่ยวข้องกับ VideoFrame. คุณสมบัตินี้เป็นอ่านอย่างเดียวและคืนค่า [`ICaptionsCollection`](../icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรึง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรึง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าออบเจ็ค EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรึง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรึงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | คืนค่าหรือกำหนดออบเจ็ควิดีโอที่ฝังไว้. อ่าน/เขียน [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าออบเจ็ค FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปทรึง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรึงบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปทรึง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรึง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรึงจะถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | กำหนดว่า VideoFrame จะถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่า PictureFrame เป็นออบเจ็ค Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'ทำเครื่องหมายว่าเป็นของตกแต่ง' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรึงถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรึงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าออบเจ็ค LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรึง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรึงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | คืนค่าหรือกำหนดชื่อของไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปทรึง. ต้องไม่เป็น null. ใช้ค่าว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า Identifier ที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรึงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรึงจากใด ๆ ในเอกสารได้อย่างเชื่อถือ. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าออบเจ็ค GroupShape พาเร้นท์ถ้ารูปทรึงถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | คืนค่าออบเจ็ค PictureFillFormat สำหรับเฟรมรูปภาพ. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | คืนค่าการล็อกของรูปทรึง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของรูปทรึง. คืนค่า null หากรูปทรึงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | กำหนดว่าวิดีโอจะทำซ้ำหรือไม่. อ่าน/เขียน Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | คืนค่าหรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเร้นท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปทรึงดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | คืนค่าหรือกำหนดสเกลความสูง (สัมพันธ์กับขนาดภาพดั้งเดิม) ของเฟรมรูปภาพ. ค่าที่ 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | คืนค่าหรือกำหนดสเกลความกว้าง (สัมพันธ์กับขนาดภาพดั้งเดิม) ของเฟรมรูปภาพ. ค่าที่ 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | กำหนดว่าวิดีโอจะย้อนกลับไปเริ่มอัตโนมัติทันทีที่ภาพยนตร์เล่นจบหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรึงที่ระบุหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | คืนค่าการล็อกของรูปทรึง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | คืนค่าออบเจ็คสไตล์ของรูปทรึง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | คืนค่าหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดของชุด [`ShapeType`](../shapetype) ยกเว้นเส้นทุกรูปแบบ: |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเร้นท์ของรูปทรึง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าออบเจ็ค ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติของรูปทรึง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรึงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | ตัดส่วนท้าย [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | ตัดส่วนเริ่มต้น [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าอิดีเทอร์ภายในระดับการนำเสนอที่ตั้งใจใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | คืนค่าหรือกำหนดระดับเสียง. อ่าน/เขียน [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรึง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปทรึง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปทรึง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรึงในลำดับ z-order. Shapes[0] คืนรูปทรึงที่อยู่ด้านหลังสุดของ z-order, และ Shapes[Shapes.Count - 1] คืนรูปทรึงที่อยู่ด้านหน้าสุดของ z-order. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้กับอันที่ระบุ |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของรูปทรึง |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่ารูปทรึง placeholder พื้นฐาน (รูปทรึงจากเลเอาต์และ/หรือสไลด์แม่ที่รูปทรึงปัจจุบันสืบทอดมา). จะคืนค่า null หากรูปทรึงปัจจุบันไม่ได้สืบทอด |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | คืนค่าสำเนาของเส้นทางของรูปทรึงเรขาคณิต. พิกัดเป็นสัมพันธ์กับมุมซ้ายบนของรูปทรึง |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าทัมบ์เนลของรูปทรึง. ประเภท ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าทัมบ์เนลของรูปทรึง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรึงที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรึงนี้ไม่ใช่ placeholder |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปทรึงจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรึง. เปลี่ยนประเภทของรูปทรึง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปทรึงจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรึง. เปลี่ยนประเภทของรูปทรึง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe)
* อินเทอร์เฟซ [IVideoFrame](../ivideoframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->