---
title: PictureFrame
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงถึงกรอบที่มีรูปภาพอยู่ภายใน.
type: docs
weight: 9430
url: /th/aspose.slides/pictureframe/
---
## PictureFrame คลาส

Represents a frame with a picture inside.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่า adjustment ของ shape. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่า shape จะถูกแสดงผลอย่างไรในโหมดสีดำ-ขาว. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของ shape. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการเติมสำหรับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบ shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ส่งคืนหรือกำหนดความสูงของ shape, วัดเป็น points. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปภาพ (shape) ถูกซ่อนไหม. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการ hyperlink. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการเม้าส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่า PictureFrame เป็นวัตถุ Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ส่งคืนหรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของ shape. ต้องไม่เป็น null. ใช้ค่า string ว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนวัตถุ GroupShape พ่อแม่หาก shape ถูกจัดกลุ่ม. มิฉะนั้นส่งคืน null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนวัตถุ PictureFillFormat สำหรับ frame ภาพ. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืน locks ของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของ shape. ส่งคืน null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติกรอบ shape ดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ส่งคืนหรือกำหนดสเกลของความสูง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ส่งคืนหรือกำหนดสเกลของความกว้าง (อ้างอิงจากขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืน locks ของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนวัตถุ style ของ shape. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในชุด [`ShapeType`](../shapetype), ยกเว้นรูปแบบเส้นทั้งหมด: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์แม่ของ shape. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนวัตถุ ThreeDFormat ซึ่งมีคุณสมบัติเอฟเฟ็กต์ 3d สำหรับ shape. หมายเหตุ: สามารถส่งคืนค่า null สำหรับ shape ประเภทบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในระดับการนำเสนอที่ออกแบบไว้สำหรับใช้โดยแอด-อินหรือโค้ดอื่น. เนื่องจากค่านี้สามารถถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | ส่งคืนหรือกำหนดความกว้างของ shape, วัดเป็น points. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | ส่งคืนหรือกำหนดพิกัด x ของมุมบนซ้ายของ shape, วัดเป็น points. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | ส่งคืนหรือกำหนดพิกัด y ของมุมบนซ้ายของ shape, วัดเป็น points. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของ shape ในลำดับ z-order. Shapes[0] คืน shape ที่อยู่ด้านหลังสุดของ z-order, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าสุดของ z-order. อ่านอย่างเดียว Int32. |

## เมธอด

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของ shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือมาสเตอร์สไลด์ที่ shape ปัจจุบันสืบทอดมาจาก). จะส่งคืน null หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของเส้นทางของ geometry shape. พิกัดอ้างอิงจากมุมซ้ายบนของ shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืน thumbnail ของ shape. ประเภท ShapeThumbnailBounds.Shape ถูกใช้โดยค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืน thumbnail ของ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | ส่งคืนขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดต geometry ของ shape จากวัตถุ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดต geometry ของ shape จากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยน Thumbnail ของ Audio Frame.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // เพิ่ม audio frame ลงในสไลด์ด้วยตำแหน่งและขนาดที่ระบุ.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // เพิ่มรูปภาพเข้าไปในทรัพยากรของการนำเสนอ.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // ตั้งค่ารูปภาพสำหรับ audio frame.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//บันทึกการนำเสนอที่แก้ไขแล้วลงดิสก์
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IPictureFrame](../ipictureframe)
* พื้นที่ชื่อ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->