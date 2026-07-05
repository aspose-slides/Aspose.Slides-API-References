---
title: AudioFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงคลิปเสียงบนสไลด์.
type: docs
weight: 870
url: /th/aspose.slides/audioframe/
---
## คลาส AudioFrame

แสดงคลิปเสียงบนสไลด์

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของรูปร่าง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | ส่งคืนหรือกำหนดดัชนีแทร็กสุดท้าย. อ่าน/เขียน Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | ส่งคืนหรือกำหนดเวลาของแทร็กสุดท้าย. อ่าน/เขียน Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | ส่งคืนหรือกำหนดดัชนีแทร็กเริ่มต้น. อ่าน/เขียน Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | ส่งคืนหรือกำหนดเวลาของแทร็กเริ่มต้น. อ่าน/เขียน Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดวิธีการแสดงรูปร่างในโหมดสีขาวดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | รับคอลเลกชันของคำอธิบายปิดที่เชื่อมโยงกับ AudioFrame. คุณสมบัตินี้อ่านอย่างเดียวและส่งคืน [`ICaptionsCollection`](../icaptionscollection) ที่มีแทร็กคำบรรยายทั้งหมด. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | กำหนดว่ามีเสียงฝังอยู่ในงานนำเสนอหรือไม่. อ่านอย่างเดียว Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | ส่งคืนหรือกำหนดอ็อบเจ็กต์เสียงฝัง. อ่าน/เขียน [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | ระบุระยะเวลาการเฟดอินเริ่มต้นของสื่อเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | ระบุระยะเวลาการเฟดเอาต์สุดท้ายของสื่อเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | กำหนดว่า AudioFrame ถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | กำหนดว่ากรอบรูปเป็นวัตถุ Cameo หรือไม่. อ่านอย่างเดียว Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก “Mark as decorative”. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | ส่งคืนหรือกำหนดชื่อไฟล์เสียงที่เชื่อมโยงกับ AudioFrame. อ่าน/เขียน String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ต่อสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจ็กต์ GroupShape แม่ถ้ารูปร่างเป็นส่วนหนึ่งของกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ส่งคืนอ็อบเจ็กต์ PictureFillFormat สำหรับกรอบรูป. อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | ส่งคืนล็อกของรูปร่าง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | กำหนดว่ามีการเล่นเสียงผ่านหลายสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | กำหนดว่าการเล่นเสียงวนซ้ำหรือไม่. อ่าน/เขียน Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | ส่งคืนหรือกำหนดโหมดการเล่นเสียง. อ่าน/เขียน [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนงานนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติดิบของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ส่งคืนหรือกำหนดอัตราส่วนความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ส่งคืนหรือกำหนดอัตราส่วนความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของกรอบรูป. ค่า 1.0 เท่ากับ 100%. อ่าน/เขียน Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | กำหนดว่าการเล่นเสียงจะรีวินด์ไปจุดเริ่มต้นโดยอัตโนมัติหลังจากเล่นเสร็จหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | ส่งคืนล็อกของรูปร่าง. อ่านอย่างเดียว [`IPictureFrameLock`](../ipictureframelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนออบเจ็กต์สไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape สำหรับ PictureFrame. มีรายการที่อนุญาตทั้งหมดในชุด [`ShapeType`](../shapetype), ยกเว้นเส้นทุกประเภท: |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | ระบุระยะเวลาที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | ระบุระยะเวลาที่จะตัดออกจากส่วนต้นของสื่อระหว่างการเล่นเป็นมิลลิวินาที. อ่าน/เขียน Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในที่ใช้ในงานนำเสนอซึ่งออกแบบมาสำหรับส่วนเสริมหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่คงที่ตลอด. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | ส่งคืนหรือกำหนดระดับเสียง. อ่าน/เขียน [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | ส่งคืนหรือกำหนดระดับเสียงเป็นเปอร์เซ็นต์. อ่าน/เขียน Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังที่สุด, ส่วน Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าที่สุด. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้กับอ็อบเจ็กต์ที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน placeholder รูปร่างพื้นฐาน (รูปร่างจากเลเอาท์หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาพาธของรูปร่างเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพย่อของรูปร่าง. ค่าเริ่มต้นใช้ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนตัวเลือกการเล่นเสียง

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // รับรูปร่าง AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // ตั้งค่าโหมดการเล่นให้เล่นเมื่อคลิก
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // ตั้งค่าเสียงเป็นต่ำ
    audioFrame.Volume = AudioVolumeMode.Low;
    // ตั้งค่าให้เสียงเล่นต่อเนื่องบนหลายสไลด์
    audioFrame.PlayAcrossSlides = true;
    // ปิดการวนลูปสำหรับเสียง
    audioFrame.PlayLoopMode = false;
    // ซ่อน AudioFrame ระหว่างการแสดงสไลด์
    audioFrame.HideAtShowing = true;
    // รีวินด์เสียงกลับไปเริ่มต้นหลังจากเล่นเสร็จ
    audioFrame.RewindAudio = true;
    // บันทึกไฟล์ PowerPoint ลงดิสก์
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe)
* อินเทอร์เฟซ [IAudioFrame](../iaudioframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->