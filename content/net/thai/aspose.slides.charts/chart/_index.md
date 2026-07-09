---
title: Chart
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 1260
url: /th/aspose.slides.charts/chart/
---
## Chart คลาส

แสดงถึงแผนภูมิกราฟิกบนสไลด์.

```csharp
public class Chart : GraphicalObject, IChart
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือ กำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือ กำหนดชื่อของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IThemeable พื้นฐาน. อ่านอย่างเดียว [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | คืนค่าออบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เชื่อมโยงกับแผนภูมิ. อ่านอย่างเดียว [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | คืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | คืนค่า หรือ กำหนดชื่อแผนภูมิ. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลที่กำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | คืนค่า หรือ กำหนดวิธีการพล็อตเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนอ็อบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนอ็อบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | คืนอ็อบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนล็อคของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | กำหนดว่าผังแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | กำหนดว่าผังแผนภูมิมีตารางบรรยายหรือไม่. อ่าน/เขียน Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | ระบุว่าพื้นที่แผนภูมิจะมีมุมโค้ง. อ่าน/เขียน Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | กำหนดว่าผังแผนภูมิมีชื่อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นแบบกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | คืนค่า หรือ กำหนดตารางบรรยายสำหรับแผนภูมิ. อ่านอย่างเดียว [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนอ็อบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ กำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่าว่าง. ใช้ค่าสตริงว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนตัวระบุที่ไม่ซ้ำกันระดับสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนอ็อบเจกต์ GroupShape พ่อแม่หากรูปร่างเป็นแบบกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนตัวตำแหน่งชั่วคราวสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | แสดงถึงพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นได้หรือไม่. false เพื่อพล็อตทั้งเซลล์ที่มองเห็นและซ่อน. อ่าน/เขียน Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติของกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ กำหนดจำนวนองศาที่รูปร่างกำหนดถูกหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิก; ค่าลบแสดงการหมุนทวนเข็มนาฬิก. อ่าน/เขียน Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | คืนการหมุน 3D ของแผนภูมิ. อ่านอย่างเดียว [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนล็อคของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | ระบุว่าป้ายข้อมูลที่เกินค่าสูงสุดของแผนภูมิจะแสดงหรือไม่. อ่าน/เขียน Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | คืนอ็อบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3D. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | คืนค่า หรือ กำหนดสไตล์ของแผนภูมิ. อ่าน/เขียน [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | คืนรูปแบบข้อความของแผนภูมิ. คุณสมบัตินี้ไม่ใช้ได้กับประเภทต่อไปนี้: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. อ่านอย่างเดียว [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | คืนผู้จัดการธีม. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | คืนค่า หรือ กำหนดประเภทของแผนภูมิ. อ่าน/เขียน [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในระดับการนำเสนอที่ตั้งไว้เพื่อใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, ไม่ควรใช้เป็นคีย์ที่ไม่ซ้ำถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | ระบุรูปร่างที่วาดบนด้านบนของแผนภูมิ. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้กับอันที่ระบุ |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | คืนธีมที่มีผลต่อแผนภูมินี้ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลเอาต์และ/หรือมาสเตอร์สไลด์ที่รูปร่างปัจจุบันสืบทอด). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพขนาดเล็กของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพขนาดเล็กของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำงานตามอินเทอร์เฟซ IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject)
* อินเทอร์เฟซ [IChart](../ichart)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->