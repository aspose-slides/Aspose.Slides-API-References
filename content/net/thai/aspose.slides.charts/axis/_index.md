---
title: Axis
second_title: Aspose.Sildes สำหรับ .NET การอ้างอิง API
description: บรรจุตัวอ็อบเจ็กต์ที่เป็นตัวแทนของแกนของแผนภูมิ
type: docs
weight: 1180
url: /th/aspose.slides.charts/axis/
---
## คลาส Axis

บรรจุตัวอ็อบเจ็กต์ที่แทนแกนของแผนภูมิ

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | ระบุหน่วยหลักที่แท้จริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | ระบุสเกลของหน่วยหลักที่แท้จริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | ระบุค่าสูงสุดที่แท้จริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | ระบุหน่วยรองที่แท้จริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | ระบุสเกลของหน่วยรองที่แท้จริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | ระบุค่าต่ำสุดที่แท้จริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าที่แท้จริง. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | แสดงประเภทการรวมของแกนประเภท (binning). ใช้กับประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | แสดงว่าดีไซน์แกนค่า (value axis) ตัดแกนประเภทที่ระหว่างประเภทหรือไม่. คุณสมบัตินี้ใช้ได้เฉพาะแกนประเภทและไม่ใช้กับแผนภูมิตรีมิติ. อ่าน/เขียน Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | ระบุความกว้างของ bin เมื่อค่าคุณสมบัติ AggregationType ตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | ระบุประเภทของแกนประเภท. อ่าน/เขียน [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | ส่งคืนแผนภูมิพาเรนต์. อ่านอย่างเดียว [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | แสดงตำแหน่งบนแกนที่แกนตั้งฉากตัดผ่าน. อ่าน/เขียน Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | แสดง CrossType บนแกนที่กำหนดซึ่งแกนอื่นตัดผ่าน. อ่าน/เขียน [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | ระบุค่าการสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | แสดงรูปแบบของแกน. อ่านอย่างเดียว [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | กำหนดว่ามีชื่อแกนที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | ระบุว่าหน่วยหลักของแกนได้รับการกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | ระบุว่าค่ามากสุดได้รับการกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | ระบุว่าหน่วยรองของแกนได้รับการกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | ระบุว่าค่าต่ำสุดได้รับการกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | ระบุค่าบิน overflow อัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | ระบุค่าระยะห่างของป้ายระดับอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickLabelSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | ระบุค่าระยะห่างของเครื่องหมายระดับอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickMarksSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | ระบุค่าบิน underflow อัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | แสดงว่าชนิดสเกลของแกนค่าคือแบบลอการิทึมหรือไม่. อ่าน/เขียน Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | ระบุว่ารูปแบบเชื่อมต่อกับข้อมูลแหล่งที่มาหรือไม่. อ่าน/เขียน Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | ระบุว่ามีการใช้ bin overflow หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิน overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | แสดงว่าการวางจุดข้อมูลของ MS PowerPoint ทำจากท้ายไปหัวหรือไม่. อ่าน/เขียน Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | ระบุว่ามีการใช้ bin underflow หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิน underflow. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | ระบุระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือแกนวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | แสดงฐานของลอการิทึม. ค่าตั้งต้นคือ 10. อ่าน/เขียน Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | แสดงรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | แสดงประเภทของเครื่องหมายระดับหลักสำหรับแกนที่กำหนด. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | แสดงสเกลของหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | แสดงค่าสูงสุดบนแกนค่า. อ่าน/เขียน Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | แสดงรูปแบบของเส้นกริดรองบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | แสดงประเภทของเครื่องหมายระดับรองสำหรับแกนที่กำหนด. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | แสดงสเกลของหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | แสดงค่าต่ำสุดบนแกนค่า. อ่าน/เขียน Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | แสดงสตริงรูปแบบสำหรับป้ายแกน. อ่าน/เขียน String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | ระบุจำนวน bin เมื่อค่าคุณสมบัติ AggregationType ตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | ระบุค่าตามกำหนดของ bin overflow. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และ IsOverflowBin เป็น true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | แสดงตำแหน่งของแกน. อ่าน/เขียน [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | เพื่อซ่อนเส้นกริดหลัก ให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | เพื่อซ่อนเส้นกริดรอง ให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | แสดงรูปแบบของข้อความ. อ่านอย่างเดียว [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | แสดงตำแหน่งของป้ายเครื่องหมายระดับบนแกนที่กำหนด. อ่าน/เขียน [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | แสดงมุมการหมุนของป้ายระดับ. อ่าน/เขียน Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | ระบุจำนวนป้ายระดับที่จะข้ามระหว่างการวาดป้าย. ใช้กับแกนประเภทหรือซีรีส์. อ่าน/เขียน UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | ระบุจำนวนเครื่องหมายระดับที่ควรข้ามก่อนวาดเครื่องหมายต่อไป. ใช้กับแกนประเภทหรือซีรีส์. อ่าน/เขียน UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | รับชื่อหัวข้อของแกน. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | ระบุค่าตามกำหนดของ bin underflow. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และ IsUnderflowBin เป็น true. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลของแกน. |

### ดูเพิ่มเติม

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->