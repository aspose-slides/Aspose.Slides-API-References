---
title: OleObjectFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนวัตถุ OLE บนสไลด์
type: docs
weight: 9230
url: /th/aspose.slides/oleobjectframe/
---
## OleObjectFrame คลาส

แทนวัตถุ OLE บนสไลด์

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนหรือกำหนดข้อความแสดงแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนหรือกำหนดชื่อเรื่องของข้อความแสดงแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | อนุญาตให้รับอินเทอร์เฟซ IGraphicalObject พื้นฐาน อ่านอย่างเดียว [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ.. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนออบเจ็กต์ EffectFormat ซึ่งบรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE อ่าน/เขียน [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | คืนชื่อไฟล์ของอ็อบเจ็กต์ OLE ที่ฝังไว้ |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | คืนพาธของอ็อบเจ็กต์ OLE ที่ฝังไว้ |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนออบเจ็กต์ FillFormat ที่บรรจุคุณลักษณะการเติมของรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณลักษณะการเติม อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนหรือกำหนดคุณสมบัติของเฟรมรูปทรง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนการล็อกของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรง หน่วยเป็นพอยท์ อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนหรือกำหนดไฮเปอร์ลิงก์สำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนหรือกำหนดไฮเปอร์ลิงก์สำหรับการวางเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'ทำเครื่องหมายเป็นประดับ' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่ อ่าน/เขียน Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนออบเจ็กต์ LineFormat ที่บรรจุคุณลักษณะการจัดรูปแบบเส้นสำหรับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณลักษณะเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | คืนพาธเต็มของไฟล์ที่เชื่อมโยง จะใช้ชื่อไฟล์สั้น อ่านอย่างเดียว String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | คืนพาธเต็มของไฟล์ที่เชื่อมโยง จะใช้ชื่อไฟล์ยาว อ่าน/เขียน String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | คืนพาธสัมพัทธ์ของไฟล์ที่เชื่อมโยง หากมี มิฉะนั้นคืนสตริงว่าง อ่านอย่างเดียว String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนหรือกำหนดชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างหากจำเป็น อ่าน/เขียน String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | คืนหรือกำหนดชื่อของวัตถุ อ่าน/เขียน String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | คืน ProgID ของวัตถุ อ่านอย่างเดียว String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนตัวระบุเฉพาะที่กำหนดโดยสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ดอินเทอร์อ็อบสามารถอ้างอิงรูปทรงจากที่ใดก็ได้ในเอกสารอย่างเชื่อถือได้ อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนออบเจ็กต์ GroupShape พ่อแม่หากรูปทรงถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนช่องสำหรับรูปทรง หากรูปทรงไม่มีช่อง จะคืนค่า null อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนการนำเสนอพ่อแม่ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนหรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนหรือกำหนดจำนวนองศาที่รูปทรงหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนการล็อกของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์พ่อแม่ของรูปทรง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | คืนออบเจ็กต์คุณสมบัติการเติมภาพ OleObject อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | คืนหรือกำหนดชื่อเรื่องสำหรับไอคอน OleObject อ่าน/เขียน String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนออบเจ็กต์ ThreeDFormat ที่มีคุณลักษณะ 3D สำหรับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณลักษณะ 3D อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในที่กำหนดโดยการนำเสนอซึ่งออกแบบเพื่อใช้โดยส่วนเสริมหรือโค้ดอื่น ๆ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม ต้องไม่พิจารณาเป็นคีย์เฉพาะถาวร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | กำหนดว่าข้อมูลฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่ อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรง หน่วยเป็นพอยท์ อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยท์ อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยท์ อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังสุดของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับออบเจ็กต์ที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาต์หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอด) จะคืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนรูปภาพย่อยของรูปทรง ShapeThumbnailBounds.Shape เป็นชนิดค่าขอบภาพย่อยโดยค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนรูปภาพย่อยของรูปทรง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตที่มองเห็นของรูปทรงที่คำนวนจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ได้เป็น placeholder |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | ตั้งค่าข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE วิธีการนี้จะเปลี่ยนคุณสมบัติของอ็อบเจ็กต์ให้สอดคล้องกับข้อมูลใหม่และตั้งค่า IsObjectLink เป็น false บ่งบอกว่าอ็อบเจ็กต์ OLE ถูกฝัง |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีเข้าถึงกรอบอ็อบเจ็กต์ OLE

```csharp
[C#]
// โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์ Presentation
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // เข้าถึงสไลด์แรก
    ISlide sld = pres.Slides[0];
    // แปลงชนิดรูปร่างเป็น OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // อ่านวัตถุ OLE และเขียนลงดิสก์
    if (oleObjectFrame != null)
    {
        // รับข้อมูลไฟล์ที่ฝังอยู่
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // รับส่วนต่อท้ายไฟล์ที่ฝังอยู่
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