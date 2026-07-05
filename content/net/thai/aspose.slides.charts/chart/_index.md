---
title: Chart
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นแผนภูมิกราฟิกบนสไลด์หนึ่ง.
type: docs
weight: 1260
url: /th/aspose.slides.charts/chart/
---
## คลาส Chart

แสดงแผนภูมิกราฟิกบนสไลด์.

```csharp
public class Chart : GraphicalObject, IChart
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | อนุญาตให้รับอินเทอร์เฟซ IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | อนุญาตให้รับอินเทอร์เฟซ IThemeable พื้นฐาน. อ่านอย่างเดียว [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังหลังของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติเชื่อกำหนดวิธีการแสดงรูปทรงในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เชื่อมโยงกับแผนภูมิ. อ่านอย่างเดียว [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | คืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | คืนค่า หรือกำหนดชื่อแผนภูมิ. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลที่กำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | คืนค่า หรือกำหนดวิธีการพล็อตเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนออบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนออบเจ็กต์ FillFormat ที่บรรจุคุณสมบัติการเติมรูปแบบสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปทรง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนการล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | ระบุตัวว่าผลกราฟมีตารางข้อมูลหรือไม่. อ่าน/เขียน Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | ระบุว่าแผนภูมิมี legend หรือไม่. อ่าน/เขียน Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | ระบุว่าพื้นที่แผนภูมิควรมีมุมโค้ง. อ่าน/เขียน Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | ระบุว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | คืนค่า หรือกำหนดความสูงของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | ระบุว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | คืนค่า หรือกำหนดตัวเลือก 'Mark as decorative' . อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | ระบุว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | ระบุว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | คืนค่า หรือกำหนด legend สำหรับแผนภูมิ. อ่านอย่างเดียว [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนออบเจ็กต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปทรง. ต้องไม่เป็นค่าว่าง. ใช้ค่าว่างเป็นสตริงหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าไอดีเฉพาะที่จำกัดในสไลด์ ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนออบเจ็กต์ GroupShape พาเรนต์หากรูปทรงเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืน placeholder ของรูปทรง. คืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | แทนพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | ระบุว่าจะแสดงเฉพาะเซลล์ที่มองเห็นได้หรือไม่. กำหนดเป็น False เพื่อพล็อตทั้งเซลล์ที่มองเห็นและที่ซ่อน. อ่าน/เขียน Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปทรงดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปทรงระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | คืนการหมุน 3D ของแผนภูมิ. อ่านอย่างเดียว [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนการล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 คุณสมบัติ) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | ระบุว่าป้ายข้อมูลที่เกินค่าสูงสุดของแผนภูมิจะต้องแสดงหรือไม่. อ่าน/เขียน Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังข้างของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์แม่ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | คืนค่า หรือกำหนดสไตล์ของแผนภูมิ. อ่าน/เขียน [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | คืนรูปแบบข้อความของแผนภูมิ. คุณสมบัตินี้ไม่ใช้กับประเภทต่อไปนี้: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. อ่านอย่างเดียว [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | คืนตัวจัดการธีม. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนออบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | คืนค่า หรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในที่จำกัดในงานนำเสนอ ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรมเมอร์ ไม่ควรใช้เป็นคีย์ที่คงที่. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | ระบุรูปทรงที่วาดบนแผนภูมิ. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | คืนค่า หรือกำหนดความกว้างของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | คืนค่า หรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | คืนค่า หรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับตัวที่ระบุ. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | คืนธีมที่มีผลสำหรับแผนภูมินี้. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูป placeholder พื้นฐาน (รูปจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพย่อของรูปทรง. ชนิด ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ใช้ IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject)
* อินเทอร์เฟซ [IChart](../ichart)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->