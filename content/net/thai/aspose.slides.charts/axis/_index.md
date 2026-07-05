---
title: Axis
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: ห่อหุ้มอ็อบเจ็กต์ที่เป็นตัวแทนแกนของแผนภูมิ
type: docs
weight: 1180
url: /th/aspose.slides.charts/axis/
---
## คลาส Axis

ห่อหุ้มอ็อบเจ็กต์ที่เป็นตัวแทนแกนของแผนภูมิ

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | ระบุหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | ระบุสเกลหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | ระบุค่ามากสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | ระบุหน่วยรองจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | ระบุสเกลหน่วยรองจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | ระบุค่าต่ำสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | แสดงประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). ใช้กับหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | แสดงว่ามีการข้ามแกนค่ากับแกนหมวดหมู่ระหว่างหมวดหมู่หรือไม่. คุณสมบัตินี้ใช้เฉพาะแกนหมวดหมู่และไม่ใช้กับแผนภูมิ 3 มิติ. อ่าน/เขียน Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | ระบุความกว้างของบิ้นเมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | ระบุประเภทของแกนหมวดหมู่. อ่าน/เขียน [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | คืนค่าแผนภูมิแม่. อ่านอย่างเดียว [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | แสดง CrossType บนแกนที่กำหนดที่แกนอื่นข้าม. อ่าน/เขียน [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | ระบุค่าการสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | แสดงรูปแบบของแกน. อ่านอย่างเดียว [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | ระบุว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | ระบุว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | ระบุค่าบิน์ overflow แบบอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | ระบุค่าการเว้นระยะป้ายกำกับติ๊กอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickLabelSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | ระบุค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ TickMarksSpacing. อ่าน/เขียน Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | ระบุค่าบิน์ underflow แบบอัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | แสดงว่าประเภทสเกลของแกนค่าคือโลการิทึมหรือไม่. อ่าน/เขียน Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | ระบุว่ารูปแบบเชื่อมกับข้อมูลต้นแหล่งหรือไม่. อ่าน/เขียน Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | ระบุว่ามีการใช้บิ้น overflow หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิ้น overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | แสดงว่า MS PowerPoint วาดจุดข้อมูลจากข้อมูลสุดท้ายไปยังแรกหรือไม่. อ่าน/เขียน Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | ระบุว่ามีการใช้บิ้น underflow หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิ้น underflow. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน/เขียน Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | ระยะห่างของป้ายกำกับจากแกน. ใช้กับแกนหมวดหมู่หรือวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | แสดงฐานของลอการิธึม. ค่าตั้งต้นคือ 10. อ่าน/เขียน Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | แสดงรูปแบบเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่กำหนด. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | แสดงค่าสูงสุดบนแกนค่า. อ่าน/เขียน Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | แสดงรูปแบบเส้นกริดรองบนแกนแผนภูมิ. อ่านอย่างเดียว [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่กำหนด. อ่าน/เขียน [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า. อ่าน/เขียน Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | แสดงค่าต่ำสุดบนแกนค่า. อ่าน/เขียน Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | แสดงสตริงรูปแบบสำหรับป้ายกำกับแกน. อ่าน/เขียน String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | ระบุจำนวนบิ้นเมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | ระบุค่าบิ้น overflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และคุณสมบัติ IsOverflowBin มีค่าเป็น true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | แสดงตำแหน่งของแกน. อ่าน/เขียน [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | เพื่อซ่อนเส้นกริดหลักตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | เพื่อซ่อนเส้นกริดรองตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | แสดงรูปแบบของข้อความ. อ่านอย่างเดียว [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | แสดงตำแหน่งของป้ายกำกับเครื่องหมายติ๊กบนแกนที่กำหนด. อ่าน/เขียน [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | แสดงมุมการหมุนของป้ายกำกับติ๊ก. อ่าน/เขียน Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | ระบุจำนวนป้ายกำกับติ๊กที่ข้ามระหว่างป้ายที่วาด. ใช้กับแกนหมวดหมู่หรือซีรีส์. อ่าน/เขียน UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | ระบุจำนวนเครื่องหมายติ๊กที่ควรข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด. ใช้กับแกนหมวดหมู่หรือซีรีส์. อ่าน/เขียน UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | รับชื่อเรื่องของแกน. อ่านอย่างเดียว [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | ระบุค่าบิ้น underflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และคุณสมบัติ IsUnderflowBin มีค่าเป็น true. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลของแกน. |

### ดูเพิ่มเติม

* คลาส [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* คลาส [AxesManager](../axesmanager)
* อินเทอร์เฟซ [IAxis](../iaxis)
* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->