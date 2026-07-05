---
title: IChart
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงแผนภูมิกราฟิกบนสไลด์.
type: docs
weight: 1740
url: /th/aspose.slides.charts/ichart/
---
## IChart อินเทอร์เฟซ

แสดงแผนภูมิกราฟิกบนสไลด์.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IFormattedTextContainer พื้นฐาน. อ่านอย่างเดียว [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IGraphicalObject พื้นฐาน. อ่านอย่างเดียว [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | ส่งคืนอินเทอร์เฟซ IOverrideThemeable. อ่านอย่างเดียว [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | ส่งคืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับแผนภูมิ. อ่านอย่างเดียว [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | ส่งคืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | ส่งคืนหรือกำหนดชื่อแผนภูมิ. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | ส่งคืนหรือกำหนดวิธีการพล็อตเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่. อ่าน/เขียน Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | ระบุว่าพื้นที่แผนภูมิควรมีมุมโค้ง. อ่าน/เขียน Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | กำหนดว่าแผนภูมิมีชื่อที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | ส่งคืนหรือกำหนดคำอธิบายสำหรับแผนภูมิ. อ่านอย่างเดียว [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | เป็นตัวแทนของพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | กำหนดว่าจะพล็อตเฉพาะเซลล์ที่มองเห็นได้เท่านั้นหรือไม่. ตั้งค่าเป็น false เพื่อพล็อตเซลล์ที่มองเห็นและเซลล์ที่ซ่อนอยู่ด้วย. อ่าน/เขียน Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | ส่งคืนการหมุน 3D ของแผนภูมิ. อ่านอย่างเดียว [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิหรือไม่. อ่าน/เขียน Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | ส่งคืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | ส่งคืนหรือกำหนดสไตล์ของแผนภูมิ. อ่าน/เขียน [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | ส่งคืนหรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | ระบุรูปร่างที่วาดอยู่บนแผนภูมิ. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำงานตามอินเทอร์เฟซ IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IFormattedTextContainer](../iformattedtextcontainer)
* อินเทอร์เฟซ [IGraphicalObject](../../aspose.slides/igraphicalobject)
* อินเทอร์เฟซ [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->