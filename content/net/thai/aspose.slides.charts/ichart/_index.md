---
title: IChart
second_title: Aspose.Sildes สำหรับการอ้างอิง API ของ .NET
description: แทนแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 1760
url: /th/aspose.slides.charts/ichart/
---
## IChart อินเทอร์เฟซ

แทนแผนภูมิกราฟิกบนสไลด์

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | อนุญาตให้ดึงส่วนต่อประสาน IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | อนุญาตให้ดึงส่วนต่อประสาน IGraphicalObject พื้นฐาน. อ่านอย่างเดียว [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | คืนค่า IOverrideThemeable. อ่านอย่างเดียว [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | ให้เข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | คืนออบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังหลังของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เชื่อมโยงกับแผนภูมิ. อ่านอย่างเดียว [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | คืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | คืนหรือกำหนดชื่อแผนภูมิ. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | คืนหรือกำหนดวิธีการพล็อตเซลล์ว่างในแผนภูมิ. อ่าน/เขียน [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | คืนออบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | กำหนดว่าแผนภูมิมีคำอธิบาย (legend) หรือไม่. อ่าน/เขียน Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | ระบุว่าพื้นที่แผนภูมิควรมีมุมโค้ง. อ่าน/เขียน Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | กำหนดว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | คืนหรือกำหนดคำอธิบาย (legend) ของแผนภูมิ. อ่านอย่างเดียว [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | แสดงพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | กำหนดว่าจะพล็อตเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่. เท็จเพื่อพล็อตทั้งเซลล์ที่มองเห็นและซ่อน. อ่าน/เขียน Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | คืนการหมุน 3 มิติของแผนภูมิ. อ่านอย่างเดียว [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | ระบุว่าจะต้องแสดงป้ายข้อมูลเมื่อเกินค่าสูงสุดของแผนภูมิหรือไม่. อ่าน/เขียน Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | คืนออบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | คืนหรือกำหนดสไตล์ของแผนภูมิ. อ่าน/เขียน [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | คืนหรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | ระบุรูปทรงที่วาดบนแผนภูมิ. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมตำแหน่งขององค์ประกอบที่ทำงานตามส่วนต่อประสาน IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IFormattedTextContainer](../iformattedtextcontainer)
* อินเทอร์เฟซ [IGraphicalObject](../../aspose.slides/igraphicalobject)
* อินเทอร์เฟซ [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* เนมสเปส [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->