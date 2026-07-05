---
title: PictureFrame
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แทนเฟรมที่มีรูปภาพอยู่ภายใน
type: docs
weight: 9410
url: /th/aspose.slides/pictureframe/
---
## คลาส PictureFrame

เป็นตัวแทนของเฟรมที่มีรูปภาพอยู่ภายใน

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของรูปทรง อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | รับหรือกำหนดข้อความอธิบายภาพที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | รับหรือกำหนดหัวข้อของข้อความอธิบายภาพที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปทรงจะถูกแสดงในโหมดสีขาว-ดำอย่างไร อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของรูปทรง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | รับหรือกำหนดคุณสมบัติของเฟรมรูปทรง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรงโดยวัดเป็นจุด อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | รับหรือกำหนด hyperlink ที่กำหนดไว้สำหรับคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนตัวจัดการ hyperlink อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | รับหรือกำหนด hyperlink ที่กำหนดไว้สำหรับเมาส์อยู่เหนือรูปทรง อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่ารูป PictureFrame นี้เป็นอ็อบเจกต์ Cameo หรือไม่ อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก “ทำเครื่องหมายว่าเป็นการตกแต่ง” อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | รับหรือกำหนดชื่อของรูปทรง ต้องไม่เป็นค่า null ใช้สตริงว่างหากต้องการ อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนรหัสประจำตัวเฉพาะของสไลด์ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือได้จากทุกตำแหน่งในเอกสาร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจกต์ GroupShape พาเรนท์ถ้ารูปทรงถูกจัดกลุ่ม มิฉะนั้นจะคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนวัตถุ PictureFillFormat สำหรับเฟรมรูปภาพ อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืนการล็อกของรูปทรง อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของรูปทรง คืนค่า null ถ้ารูปทรงไม่มี placeholder อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนพรีเซนเทชันพาเรนท์ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | รับหรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | รับหรือกำหนดอัตราส่วนของความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 เท่ากับ 100% อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | รับหรือกำหนดอัตราส่วนของความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 เท่ากับ 100% อ่าน/เขียน Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | รับหรือกำหนดจำนวนองศาที่รูปทรงจะหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืนการล็อกของรูปทรง อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนอ็อบเจกต์สไตล์ของรูปทรง อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | รับหรือกำหนดประเภท AutoShape สำหรับ PictureFrame มีรายการที่อนุญาตทั้งหมดในชุด [`ShapeType`](../shapetype) ยกเว้นเส้นทุกประเภท: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนท์ของรูปทรง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนรหัสภายในที่สโคปของพรีเซนเทชันซึ่งออกแบบมาสำหรับใช้โดยแอด-อินหรือโค้ดอื่น เนื่องจากค่าที่นี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่คงที่ อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรงโดยวัดเป็นจุด อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรงโดยวัดเป็นจุด อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรงโดยวัดเป็นจุด อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังสุดของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ตามที่ระบุ |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาเรย์ขององค์ประกอบของรูปทรง |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน placeholder รูปทรงพื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมาจาก) คืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาเส้นทางของรูปทรงเรขาคณิต พิกัดสัมพันธ์กับมุมซ้ายบนของรูปทรง |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนรูปย่อของรูปทรง ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนรูปย่อของรูปทรง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจกต์ [`IGeometryPath`](../igeometrypath) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรง เปลี่ยนประเภทของรูปทรง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปทรงจากอาเรย์ของ [`IGeometryPath`](../igeometrypath) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปทรง เปลี่ยนประเภทของรูปทรง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนรูปย่อของ Audio Frame

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // เพิ่มเฟรมเสียงไปยังสไลด์ด้วยตำแหน่งและขนาดที่ระบุ.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // เพิ่มรูปภาพไปยังทรัพยากรของพรีเซนเทชัน.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // ตั้งค่ารูปภาพสำหรับเฟรมเสียง.
	//บันทึกพรีเซนเทชันที่แก้ไขแล้วลงดิสก์
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* class [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->