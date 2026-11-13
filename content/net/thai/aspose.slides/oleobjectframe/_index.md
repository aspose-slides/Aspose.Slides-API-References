---
title: OleObjectFrame
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงถึงวัตถุ OLE บนสไลด์
type: docs
weight: 9250
url: /th/aspose.slides/oleobjectframe/
---
## OleObjectFrame คลาส

แสดงถึงวัตถุ OLE บนสไลด์.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า或กำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า或กำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | อนุญาตให้รับอินเทอร์เฟซ IGraphicalObject เบื้องต้น อ่านอย่างเดียว [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของรูปทรง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีผลเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่ อ่าน/เขียน [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | คืนค่าชื่อไฟล์ของวัตถุ OLE ที่ฝังอยู่ |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | คืนค่าที่อยู่ของวัตถุ OLE ที่ฝังอยู่ |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติของเฟรมรูปทรง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรง วัดเป็นพอยต์ อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเมาส์ผ่าน อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'ทำเครื่องหมายเป็นของตกแต่ง' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | กำหนดว่าวัตถุจะมองเห็นเป็นไอคอนหรือไม่ อ่าน/เขียน Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | คืนค่าที่อยู่เต็มของไฟล์ที่เชื่อมโยง ชื่อไฟล์สั้นจะถูกใช้ อ่านอย่างเดียว String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | คืนค่าที่อยู่เต็มของไฟล์ที่เชื่อมโยง ชื่อไฟล์ยาวจะถูกใช้ อ่าน/เขียน String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | คืนค่าที่อยู่สัมพันธ์ของไฟล์ที่เชื่อมโยงหากมีอยู่ มิฉะนั้นคืนค่าสตริงว่าง อ่านอย่างเดียว String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ กำหนดชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างหากจำเป็น อ่าน/เขียน String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | คืนค่า หรือ กำหนดชื่อของวัตถุ อ่าน/เขียน String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | คืนค่า ProgID ของวัตถุ อ่านอย่างเดียว String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าอัตลักษณ์เฉพาะสไลด์ที่ไม่ซ้ำกันซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32 ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape แม่ถ้ารูปทรงเป็นกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตำแหน่งที่กำหนดไว้ล่วงหน้าของรูปทรง คืนค่า null หากรูปทรงไม่มีตำแหน่งที่กำหนดไว้ล่วงหน้า อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติของเฟรมรูปทรงดิบ อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ กำหนดจำนวนองศาที่รูปทรงที่กำหนดหมุนรอบแกน z ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าหน้าสไลด์แม่ของรูปทรง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | คืนค่าอ็อบเจ็กต์คุณสมบัติการเติมรูปภาพของ OleObject อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | คืนค่า หรือ กำหนดชื่อเรื่องสำหรับไอคอน OleObject อ่าน/เขียน String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าอัตลักษณ์ภายในที่กำหนดขอบเขตการนำเสนอสำหรับการใช้โดยแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือว่าเป็นคีย์เฉพาะที่คงที่ อ่านอย่างเดียว UInt32 ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | กำหนดว่าวัตถุฝังที่เชื่อมโยงจะอัปเดตอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่ อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรง วัดเป็นพอยต์ อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง วัดเป็นพอยต์ อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง วัดเป็นพอยต์ อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว Int32. |

## วิธีการ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มตำแหน่งที่กำหนดไว้ล่วงหน้าใหม่หากไม่มีและตั้งค่าคุณสมบัติตำแหน่งที่กำหนดไว้ล่วงหน้าเป็นค่าเฉพาะ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่าอ็อบเจ็กต์รูปทรงตำแหน่งที่กำหนดไว้ล่วงหน้าพื้นฐาน (รูปทรงจากเค้าโครงและ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมา) จะคืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่ารูปย่อของรูปทรง ShapeThumbnailBounds.Shape ประเภทขอบเขตรูปย่อของรูปทรงจะถูกใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่ารูปย่อของรูปทรง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ตำแหน่งที่กำหนดไว้ล่วงหน้า |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | ตั้งค่าข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่ วิธีนี้เปลี่ยนคุณสมบัติของวัตถุเพื่อสะท้อนข้อมูลใหม่และตั้งค่า IsObjectLink เป็น false แสดงว่าวัตถุ OLE ถูกฝังอยู่ |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG |

### ตัวอย่าง

The following example shows how to accessing OLE Object frames.

```csharp
[C#]
// โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์การนำเสนอ
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // เข้าถึงสไลด์แรก
    ISlide sld = pres.Slides[0];
    // แปลงรูปทรงเป็น OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // อ่านวัตถุ OLE แล้วเขียนลงดิสก์
    if (oleObjectFrame != null)
    {
        // ดึงข้อมูลไฟล์ที่ฝังอยู่
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // ดึงส่วนขยายไฟล์ที่ฝังอยู่
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // สร้างเส้นทางเพื่อบันทึกไฟล์ที่สกัดออกมา
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // บันทึกข้อมูลที่สกัดออกมา
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [IOleObjectFrame](../ioleobjectframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->