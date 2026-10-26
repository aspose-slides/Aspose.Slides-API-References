---
title: AudioFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนคลิปเสียงบนสไลด์
type: docs
weight: 870
url: /th/aspose.slides/audioframe/
---
## AudioFrame คลาส

แทนคลิปเสียงบนสไลด์

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความอธิบายภาพทางเลือกที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวข้อของข้อความอธิบายภาพทางเลือกที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | ส่งคืนหรือกำหนดดัชนีแทร็กสุดท้าย. อ่าน/เขียน Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | ส่งคืนหรือกำหนดเวลาที่แทร็กสุดท้าย. อ่าน/เขียน Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | ส่งคืนหรือกำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | ส่งคืนหรือกำหนดเวลาที่แทร็กเริ่มต้น. อ่าน/เขียน Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ AudioFrame. คุณสมบัตินี้อ่านอย่างเดียวและส่งคืน [`ICaptionsCollection`](../icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของ shape. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปประเภทที่ไม่มีคุณสมบัติ effect. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | กำหนดว่ามีเสียงฝังในงานนำเสนอหรือไม่. อ่านอย่างเดียว Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | ส่งคืนหรือกำหนดอ็อบเจ็กต์เสียงที่ฝังอยู่. อ่าน/เขียน [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | ระบุตัวระยะเวลา (มิลลิวินาที) ของการเฟดอินเริ่มต้นของสื่อ. อ่าน/เขียน Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | ระบุตัวระยะเวลา (มิลลิวินาที) ของการเฟดเอาต์สุดท้ายของสื่อ. อ่าน/เขียน Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติกรอบการเติมสีสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปประเภทที่ไม่มีคุณสมบัติ fill. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของเฟรม shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของ shape หน่วยเป็น point. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่า shape ถูกซ่อนไว้หรือไม่. อ่าน/เขียน Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | กำหนดว่า AudioFrame ถูกซ่อนไว้หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนตัวจัดการ hyperlink. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่า PictureFrame เป็นวัตถุ Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก “Mark as decorative”. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่า shape อยู่ในกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติกรอบเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปประเภทที่ไม่มีคุณสมบัติ line. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | ส่งคืนหรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่ไม่ซ้ำภายในสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนวัตถุ GroupShape พาเรนท์ถ้า shape อยู่ในกลุ่ม มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนวัตถุ PictureFillFormat สำหรับ picture frame. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืนล็อกของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของ shape. คืนค่า null ถ้า shape ไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | กำหนดว่าเสียงจะเล่นต่อเนื่องข้ามสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | กำหนดว่าเสียงจะวนซ้ำหรือไม่. อ่าน/เขียน Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | ส่งคืนหรือกำหนดโหมดการเล่นเสียง. อ่าน/เขียน [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนงานนำเสนอพาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติ raw ของเฟรม shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ส่งคืนหรือกำหนดอัตราการปรับความสูงของ picture frame (อิงจากขนาดรูปต้นฉบับ). ค่า 1.0 แทน 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ส่งคืนหรือกำหนดอัตราการปรับความกว้างของ picture frame (อิงจากขนาดรูปต้นฉบับ). ค่า 1.0 แทน 100%. อ่าน/เขียน Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | กำหนดว่าเสียงจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นหลังการเล่นหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่ shape จะหมุนรอบแกน Z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืนล็อกของ shape. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนออบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในชุด [`ShapeType`](../shapetype) ยกเว้นประเภทเส้นทั้งหมด: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนท์ของ shape. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติ 3D สำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | ระบุตัวระยะเวลาที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | ระบุตัวระยะเวลาที่จะตัดออกจากส่วนต้นของสื่อระหว่างการเล่น, หน่วยเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในระดับงานนำเสนอที่ออกแบบสำหรับใช้งานโดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์คงที่ที่ไม่ซ้ำกัน. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | ส่งคืนหรือกำหนดระดับเสียงของ audio. อ่าน/เขียน [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | ส่งคืนหรือกำหนดระดับเสียงของ audio เป็นเปอร์เซ็นต์. อ่าน/เขียน Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของ shape หน่วยเป็น point. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็น point. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็น point. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืนค่า shape ที่อยู่ด้านหลังสุดของลำดับ z, ส่วน Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าสุด. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้กับออบเจ็กต์ที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของ shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน placeholder shape พื้นฐาน (shape จากเลเอาท์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมา). คืนค่า null หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาเส้นทางของ shape ทางเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืน thumbnail ของ shape. ค่าเริ่มต้นใช้ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืน thumbnail ของ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตที่มองเห็นของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | ปรับอ.geometry ของ shape จากออบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | ปรับ geometry ของ shape จากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนตัวเลือกการเล่นเสียง

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // รับ shape AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // ตั้งค่าโหมดการเล่นให้เล่นเมื่อคลิก
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // ตั้งระดับเสียงเป็น Low
    audioFrame.Volume = AudioVolumeMode.Low;
    // ตั้งค่าให้เสียงเล่นต่อเนื่องทั่วสไลด์
    audioFrame.PlayAcrossSlides = true;
    // ปิดการทำลูปสำหรับเสียง
    audioFrame.PlayLoopMode = false;
    // ซ่อน AudioFrame ระหว่างการแสดงสไลด์
    audioFrame.HideAtShowing = true;
    // รีวินด์เสียงกลับไปเริ่มต้นหลังการเล่น
    audioFrame.RewindAudio = true;
    // บันทึกไฟล์ PowerPoint ไปยังดิสก์
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe)
* อินเทอร์เฟซ [IAudioFrame](../iaudioframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->