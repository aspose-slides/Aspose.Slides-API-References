---
title: VideoFrame
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของคลิปวิดีโอบนสไลด์.
type: docs
weight: 11720
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับรูปทรง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดชื่อของข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับเฟรมวิดีโอ. คุณสมบัตินี้เป็นอ่านอย่างเดียวและส่งคืน [`ICaptionsCollection`](../icaptionscollection) ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเสียง. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | ส่งคืนหรือกำหนดอ็อบเจ็กต์วิดีโอที่ฝังไว้. อ่าน/เขียน [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติกำหนดการเติมสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | กำหนดว่าหนึ่งวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน/เขียน Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | กำหนดว่า VideoFrame ถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่า PictureFrame เป็นอ็อบเจ็กต์ Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบ Boolean. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติกำหนดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | ส่งคืนหรือกำหนดชื่อไฟล์วิดีโอที่เชื่อมโยงกับ VideoFrame. อ่าน/เขียน String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนอ็อบเจ็กต์ PictureFillFormat สำหรับเฟรมภาพ. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืนการล็อคของรูปร่าง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | กำหนดว่าวิดีโอวนซ้ำหรือไม่. อ่าน/เขียน Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | ส่งคืนหรือกำหนดโหมดการเล่นวิดีโอ. อ่าน/เขียน [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของเฟรมรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ส่งคืนหรือกำหนดอัตราส่วนความสูง (อ้างอิงจากขนาดภาพต้นฉบับ) ของเฟรมภาพ. ค่า 1.0 เทียบกับ 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ส่งคืนหรือกำหนดอัตราส่วนความกว้าง (อ้างอิงจากขนาดภาพต้นฉบับ) ของเฟรมภาพ. ค่า 1.0 เทียบกับ 100%. อ่าน/เขียน Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | กำหนดว่าวิดีโอจะรีวินด์ไปจุดเริ่มต้นโดยอัตโนมัติเมื่อตอนจบการเล่น. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืนการล็อคของรูปร่าง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนอ็อบเจ็กต์สไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดของชุด [`ShapeType`](../shapetype), ยกเว้นเส้นทุกรูปแบบ: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเสียง 3 มิติสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | ตัดส่วนท้าย [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | ตัดส่วนเริ่มต้น [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในระดับการนำเสนอที่ออกแบบให้ใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | ส่งคืนหรือกำหนดระดับเสียง. อ่าน/เขียน [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าเฉพาะที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและคืนค่าแถวขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของเส้นทางของรูปร่างเรขาคณิต. พิกัดอ้างอิงจากมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพย่อของรูปร่าง. ประเภท ShapeThumbnailBounds.Shape ของขอบเขตภาพย่อของรูปร่างถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe)
* อินเทอร์เฟซ [IVideoFrame](../ivideoframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->