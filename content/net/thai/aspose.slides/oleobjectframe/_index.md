---
title: OleObjectFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงอ็อบเจ็กต์ OLE บนสไลด์
type: docs
weight: 9230
url: /th/aspose.slides/oleobjectframe/
---
## คลาส OleObjectFrame

แสดงอ็อบเจ็กต์ OLE บนสไลด์

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน/เขียน String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | ให้เข้าถึงอินเทอร์เฟซ IGraphicalObject พื้นฐาน อ่านอย่างเดียว [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | กำหนดวิธีการแสดงรูปทรงในโหมดสีดำ-ขาว อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่า EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: อาจเป็น null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่ อ่าน/เขียน [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | คืนชื่อไฟล์ของอ็อบเจ็กต์ OLE ที่ฝังอยู่ |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | คืนเส้นทางของอ็อบเจ็กต์ OLE ที่ฝังอยู่ |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่า FillFormat ที่บรรจุคุณสมบัติการเติมสำหรับรูปทรง หมายเหตุ: อาจเป็น null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปทรง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อคของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรงเป็นจุด อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าเมเนเจอร์ของไฮเปอร์ลิงก์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเม้าส์อยู่เหนือรูปทรง อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก “Mark as decorative” อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | กำหนดว่ามีการแสดงอ็อบเจ็กต์เป็นไอคอนหรือไม่ อ่าน/เขียน Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | กำหนดว่าอ็อบเจ็กต์เชื่อมโยงกับไฟล์ภายนอกหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่า LineFormat ที่บรรจุคุณสมบัติการวาดเส้นสำหรับรูปทรง หมายเหตุ: อาจเป็น null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | คืนพาธเต็มของไฟล์ที่เชื่อมโยง จะใช้ชื่อไฟล์สั้น อ่านอย่างเดียว String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | คืนพาธเต็มของไฟล์ที่เชื่อมโยง จะใช้ชื่อไฟล์ยาว อ่าน/เขียน String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | คืนเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยง หากไม่มีจะคืนสตริงว่าง อ่านอย่างเดียว String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปทรง ห้ามเป็น null ใช้ค่าว่างหากต้องการ อ่าน/เขียน String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | คืนค่า หรือกำหนดชื่อของอ็อบเจ็กต์ อ่าน/เขียน String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | คืนค่า ProgID ของอ็อบเจ็กต์ อ่านอย่างเดียว String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า ID ที่ไม่ซ้ำของสไลด์ที่คงที่ตลอดอายุรูปทรงและใช้ให้ PowerPoint หรือโค้ด interop อ้างอิงรูปทรงได้จากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนอ็อบเจ็กต์ GroupShape พาเรนต์ถ้ารูปทรงถูกจัดกลุ่ม มิฉะนั้นคืน null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืน placeholder ของรูปทรง หากไม่มี placeholder จะคืน null อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนพาเรนต์ของการนำเสนอของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติแบบดิบของกรอบรูปทรง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงถูกหมุนรอบแกน Z ค่าเป็นบวกหมายถึงหมุนตามเข็มนาฬิกา, ค่าเป็นลบหมายถึงหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าล็อคของรูปทรง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์แม่ของรูปทรง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | คืนอ็อบเจ็กต์คุณสมบัติการเติมรูปภาพของ OleObject อ่านอย่างเดียว [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของไอคอน OleObject อ่าน/เขียน String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่า ThreeDFormat ที่บรรจุคุณสมบัติเสียง 3 มิติของรูปทรง หมายเหตุ: อาจเป็น null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในที่ใช้สำหรับการทำงานของแอด-อินหรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม ไม่ควรถือเป็นคีย์ที่คงที่ อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | กำหนดว่าอ็อบเจ็กต์ฝังที่เชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอ อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรงเป็นจุด อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด X ของมุมบน-ซ้ายของรูปทรงเป็นจุด อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด Y ของมุมบน-ซ้ายของรูปทรงเป็นจุด อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปทรงในลำดับ Z. Shapes[0] คือรูปทรงที่อยู่ด้านหลังสุด, Shapes[Shapes.Count-1] คือรูปทรงที่อยู่ด้านหน้าสุด อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืน placeholder shape พื้นฐาน (shape จากเลย์เอาต์หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอด) คืน null หาก shape ปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพย่อของรูปทรง ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปทรง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดให้รูปทรงนี้ไม่ใช่ placeholder |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | ตั้งค่าข้อมูลเกี่ยวกับ OLE ที่ฝังอยู่ วิธีการนี้จะเปลี่ยนคุณสมบัติของอ็อบเจ็กต์ให้สอดคล้องกับข้อมูลใหม่และตั้งค่า IsObjectLink เป็น false ซึ่งบ่งบอกว่าอ็อบเจ็กต์ OLE ถูกฝังอยู่ |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการเข้าถึงเฟรมอ็อบเจ็กต์ OLE

```csharp
[C#]
// โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์การนำเสนอ
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // เข้าถึงสไลด์แรก
    ISlide sld = pres.Slides[0];
    // แคสต์รูปร่างเป็น OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // อ่านอ็อบเจ็กต์ OLE และเขียนลงดิสก์
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

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->