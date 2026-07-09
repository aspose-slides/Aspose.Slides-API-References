---
title: IChart
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 1740
url: /th/aspose.slides.charts/ichart/
---
## IChart อินเทอร์เฟซ

Represents an graphic chart on a slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | อนุญาตให้รับอินเทอร์เฟซ IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | อนุญาตให้รับอินเทอร์เฟซ IGraphicalObject พื้นฐาน. อ่านอย่างเดียว [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | คืนค่าอินเทอร์เฟซ IOverrideThemeable. อ่านอย่างเดียว [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | คืนค่าอ็อบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับแผนภูมิ. อ่านอย่างเดียว [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | คืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | คืนหรือกำหนดชื่อแผนภูมิ. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | คืนหรือกำหนดวิธีการแสดงเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | คืนค่าอ็อบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่. อ่าน/เขียน Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | กำหนดให้พื้นที่แผนภูมิมีมุมโค้ง. อ่าน/เขียน Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | กำหนดว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | คืนหรือกำหนดคำอธิบายสำหรับแผนภูมิ. อ่านอย่างเดียว [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | แสดงถึงพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | กำหนดว่าจะพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่. กำหนดเป็น false เพื่อพล็อตทั้งเซลล์ที่มองเห็นและที่ซ่อนอยู่. อ่าน/เขียน Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | คืนการหมุน 3 มิติของแผนภูมิ. อ่านอย่างเดียว [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | กำหนดว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิหรือไม่. อ่าน/เขียน Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | คืนค่าอ็อบเจกต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | คืนหรือกำหนดสไตล์ของแผนภูมิ. อ่าน/เขียน [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | คืนหรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | กำหนดรูปร่างที่วาดบนแผนภูมิ. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำงานตาม IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IFormattedTextContainer](../iformattedtextcontainer)
* อินเทอร์เฟซ [IGraphicalObject](../../aspose.slides/igraphicalobject)
* อินเทอร์เฟซ [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->